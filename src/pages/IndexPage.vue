<template>
  <q-page class="flex column flex-center">
    <div
      class="pagewrap fit row wrap justify-center items-center content-center"
    >
      <div
        class="q-py-xl column delay_0 animated flipInX col-xs-12 col-md-3 content-center"
      >
        <img
          alt="logo"
          src="~assets/logo-white.svg"
          style="width: 80%"
          class="logo"
        />
      </div>
      <div class="column col-md-7 justify-center content-center">
        <div class="delay_1 animated flipInX text-h3">Hi there!</div>
        <div class="q-pb-sm delay_2 animated fadeInDown text-h4">
          The name's
        </div>
        <div class="q-py-sm delay_3 animated jackInTheBox text-h1">
          Josh Zinsser
        </div>
        <div class="delay_4 animated flipInX text-h2">
          I'm in the Web Dev game.
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
