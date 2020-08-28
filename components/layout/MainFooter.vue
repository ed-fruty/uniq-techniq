<template>
  <footer class="footer"
          :class="{[`footer-${type}`]: type}"
          :data-background-color="backgroundColor">
    <div class="container">
      <a class="footer-brand" href="#pablo">
        <img src="/img/logo_text_inline_white.svg" width="180">
      </a>
      <ul class="pull-center">
        <li>
          <a href="#">
            EVENTS
          </a>
        </li>
        <li>
          <a href="#">
            Unser Team
          </a>
        </li>
        <li>
          <a href="#">
            Über uns
          </a>
        </li>
        <li>
          <a href="#">
            Kontakt
          </a>
        </li>
      </ul>
      <ul class="social-buttons pull-right">
        <li>
          <a href="https://twitter.com" target="_blank"
             class="btn btn-icon btn-link btn-neutral">
            <i class="fab fa-twitter"></i>
          </a>
        </li>
        <li>
          <a href="https://www.facebook.com" target="_blank"
             class="btn btn-icon btn-neutral btn-link">
            <i class="fab fa-facebook-square"></i>
          </a>
        </li>
        <li>
          <a href="https://www.instagram.com" target="_blank"
             class="btn btn-icon btn-neutral btn-link">
            <i class="fab fa-instagram"></i>
          </a>
        </li>
      </ul>
    </div>
  </footer>
</template>
<script>
  export default {
    props: {
      backgroundColor: String,
      type: String
    },
    data() {
      return {
        year: new Date().getFullYear()
      }
    }
  }
</script>
<style>
</style>
