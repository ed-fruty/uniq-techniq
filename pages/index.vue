<template>
  <div class="wrapper landing-page">
    <div class="page-header header-filter">
      <div class="page-header-image"
           style="background-image: url('img/hero_1.jpg')">
      </div>
      <div class="content-center">
        <div class="container text-left">
          <div class="content-center">
            <div class="row">
              <div class="col ml-auto mr-auto text-center">
                <h1 class="title">uniQ-techniQ</h1>
                <h4 class="description ">is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
                  the industry's standard dummy text ever since the 1500s.</h4>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="events" class="section section-event">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">Events</h2>
            <h5 class="description">is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
              the industry's standard dummy text ever since the 1500s.</h5>
            <div class="section-space"></div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4">
            <card>
              <a slot="image" href="#" target="_blank">
                <img class="img-raised rounded"
                     src="/img/event_1.png"/>
              </a>


              <a href="#" target="_blank">
                <h4 class="card-title">Event</h4>
              </a>
              <h6 class="category text-success">08.Aug 2020</h6>
              <p class="card-description">is simply dummy text of the printing and typesetting industry.is simply dummy
                text of the printing and typesetting industry
              </p>

            </card>
          </div>
          <div class="col-md-4">
            <card>
              <a slot="image" href="#" target="_blank">
                <img class="img-raised rounded"
                     src="/img/event_1.png"/>
              </a>


              <a href="#" target="_blank">
                <h4 class="card-title">Event</h4>
              </a>
              <h6 class="category text-success">08.Aug 2020</h6>
              <p class="card-description">is simply dummy text of the printing and typesetting industry.is simply dummy
                text of the printing and typesetting industry
              </p>

            </card>
          </div>
          <div class="col-md-4">
            <card>
              <a slot="image" href="#" target="_blank">
                <img class="img-raised rounded"
                     src="/img/event_1.png"/>
              </a>


              <a href="#" target="_blank">
                <h4 class="card-title">Event</h4>
              </a>
              <h6 class="category text-success">08.Aug 2020</h6>
              <p class="card-description">is simply dummy text of the printing and typesetting industry.is simply dummy
                text of the printing and typesetting industry
              </p>

            </card>
          </div>
        </div>
      </div>
    </div>

    <div id="about" class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col ml-auto mr-auto text-center">
            <h2 class="title">Wer sind wir?</h2>
            <h5 class="description">is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
              the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
              scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
              electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release
              of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software
              like Aldus PageMaker including versions of Lorem Ipsum.</h5>
          </div>
        </div>
        <div class="separator separator-success"></div>
      </div>
    </div>

    <div id="team" class="testimonials-1 section-image" style="background-image: url('img/hero_2.jpg')">
      <div class="container">
        <div class="row">
          <div class="col ml-auto mr-auto text-center">
            <h2 class="title">Unser Team</h2>
            <h4 class="description text-white">Lorem Ipsum has been
              the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
              scrambled it to make a type specimen book.</h4>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6">
            <card type="testimonial">
              <img slot="avatar" class="img img-raised" src="img/michael.jpg">
              <div class="card-footer">
                <h4 class="card-title">Ivan Biljesko</h4>
              </div>
              <p class="card-description">
                It has survived not only five centuries, but also the leap into
                electronic typesetting, remaining essentially unchanged
              </p>
            </card>
          </div>
          <div class="col-md-6">
            <card type="testimonial">
              <img slot="avatar" class="img img-raised" src="img/mike.jpg">
              <div class="card-footer">
                <h4 class="card-title">Slaven Biljesko</h4>
              </div>
              <p class="card-description">
                It has survived not only five centuries, but also the leap into
                electronic typesetting, remaining essentially unchanged
              </p>
            </card>
          </div>
        </div>
      </div>
    </div>

    <div id="contact" class="section">
      <div class="contact-page">
        <div class="container">
          <div class="row">
            <div class="col-md-4 ml-auto">
              <info-section type="primary"
                            icon="now-ui-icons location_pin">
                <h4 class="info-title">Unser Büro</h4>
                <p> Eine strasse 4,
                  <br> 10000 Zagreb,
                  <br> Hrvatska
                </p>
              </info-section>
            </div>
            <div class="col-md-4 ml-auto">
              <info-section type="info"
                            icon="now-ui-icons tech_mobile">
                <h4 class="info-title">Rufen Sie uns an</h4>
                <p> Michael Jordan
                  <br> +49 123 456 458
                  <br> Mon - Fri, 8:00-22:00
                </p>
              </info-section>
            </div>
            <div class="col-md-4 ml-auto">
              <info-section type="success"
                            icon="business_briefcase-24 now-ui-icons">
                <h4 class="info-title">Legal Information</h4>
                <p> UNIQ-TECHNIQ GmbH.
                  <br> VAT  · EN2341241
                  <br> IBAN · EN8732ENGB2300099123
                  <br> Bank · Austria Bank
                </p>
              </info-section>
            </div>
          </div>

        </div>
      </div>

    </div>
  </div>
</template>
<script>
  import {Card, Button, FormGroupInput, Tabs, TabPane, InfoSection} from '@/components';
  import initParallax from '@/utils/initParallax'

  export default {
    name: 'landing-page',
    layout: 'gray-footer',
    components: {
      InfoSection,
      Card,
      Tabs,
      TabPane,
      [Button.name]: Button,
      [FormGroupInput.name]: FormGroupInput
    },
    data() {
      return {
        form: {
          firstName: '',
          email: '',
          message: ''
        }
      }
    },
    mounted() {
      initParallax()
    }
  }
</script>
<style>
</style>
