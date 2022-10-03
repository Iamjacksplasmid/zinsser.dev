<template>
  <q-page class="flex column flex-center">
    <div
      class="full-width row wrap justify-center items-stretch content-stretch"
    >
      <div class="col-12 col-md-10">
        <q-carousel
          v-model="slide"
          transition-prev="jump-left"
          transition-next="jump-right"
          swipeable
          animated
          control-color="white"
          prev-icon="arrow_left"
          next-icon="arrow_right"
          navigation-icon="radio_button_unchecked"
          navigation
          padding
          arrows
          height="80vh"
          width="100%"
          class="text-white shadow-1 rounded-borders"
        >
          <q-carousel-slide
            name="care_fall"
            class="bg-care column no-wrap flex-center"
          >
            <div class="slide_label text-h4 text-weight-bold">
              Client: CARE International
            </div>
            <q-card class="card">
              <q-card-section>
                <h4>Care Fall Newsletter</h4>
              </q-card-section>

              <q-card-section class="q-pt-none text-body2">
                This project involved assembling an eNewsletter that matched the
                content of a print newsletter being sent to donors, as well as
                an email that summarized the stories and linked to each one
                individually. It was a rare example where I handled pretty much
                every aspect of the digital side...it wasn't unusual to handle
                asset creation and layout in the email, but I also developed the
                landing page and even wrote the copy for this one. I think it
                turned out pretty well.
              </q-card-section>
            </q-card>
            <iframe
              style="border: 1px solid rgba(0, 0, 0, 0.1)"
              src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FCqYkiQNxYFtY2P7VdjFL3N%2F20-0893-Fall-eNewsletter%3Fpage-id%3D0%253A1%26node-id%3D24%253A4%26viewport%3D221%252C454%252C0.06%26scaling%3Dscale-down-width"
              allowfullscreen
            ></iframe>
          </q-carousel-slide>
          <q-carousel-slide
            name="tv"
            class="bg-care column no-wrap flex-center"
          >
            <iframe
              style="border: 1px solid rgba(0, 0, 0, 0.1)"
              src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FugOTg4igGmYxo77C8ewU6O%2F20-0679-July-Water%3Fpage-id%3D0%253A1%26node-id%3D10%253A206%26viewport%3D347%252C323%252C0.08%26scaling%3Dscale-down-width"
              allowfullscreen
            ></iframe>
          </q-carousel-slide>
          <q-carousel-slide name="layers" class="column no-wrap flex-center">
            <q-icon name="layers" size="56px" />
            <div class="q-mt-md text-center">
              {{ lorem }}
            </div>
          </q-carousel-slide>
          <q-carousel-slide name="map" class="column no-wrap flex-center">
            <q-icon name="terrain" size="56px" />
            <div class="q-mt-md text-center">
              {{ lorem }}
            </div>
          </q-carousel-slide>
        </q-carousel>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "IndexPage",
  setup() {
    return {
      slide: ref("care_fall"),
    };
  },
});
</script>
