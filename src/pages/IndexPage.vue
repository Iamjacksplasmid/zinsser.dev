<template>
  <q-page class="flex column flex-center">
    <div class="tall fit row wrap justify-center items-center content-center">
      <div
        class="logowrap q-py-xl column delay_0 animated flipInX col-xs-12 col-md-3"
      >
        <img
          alt="logo"
          src="~assets/logo-white.svg"
          style="width: 70%"
          class="logo"
        />
      </div>
      <div class="column col-md-7 justify-center content-center">
        <div class="delay_1 animated flipInX text-h2">Hi there!</div>
        <div class="q-py-md delay_2 animated fadeInDown text-h4">
          The name's
        </div>
        <div class="q-pb-lg delay_3 animated jackInTheBox text-h1">
          Josh Zinsser
        </div>
        <div class="delay_4 animated flipInX text-h2">
          I'm in the Web Dev game.
        </div>
      </div>
    </div>
    <div class="tall fit row wrap justify-center items-center content-center">
      <div class="col-xs-12 col-md-6 text-h5">
        I used to be a drafter, but that wasn't working out for me.<br />
        <br />
        I started learning how to code around 2016, but it wasn't until 2018
        that I decided to commit entirely to a career in web development.
        <br /><br />
        I spent a few years slinging <b style="color: saddlebrown">coffee</b>,
        teaching myself how to code, and assisting on freelance projects for
        other developers. <br /><br />
        Now, I specialized in frontend web development, marketing automation,
        and UI/UX design.
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
