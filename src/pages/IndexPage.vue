<template>
  <q-page class="flex column flex-center">
    <div
      class="pagewrap fit row wrap justify-center items-center content-center"
    >
      <div
        class="column delay_0 animated flipInX col-xs-12 col-md-3 content-end"
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
        <br />
      </div>
    </div>
    <div class="q-pa-lg row no-wrap justify-around content-around">
      >
      <q-btn
        href="mailto: zinssej@gmail.com"
        target="_blank"
        rounded
        outline
        class="linkButton"
        icon="fa-solid fa-paper-plane"
      />
      <q-btn
        href="https://github.com/Iamjacksplasmid"
        target="_blank"
        rounded
        outline
        class="q-mx-md linkButton"
        icon="fa-brands fa-github"
      />
      <q-btn
        href="https://www.linkedin.com/in/joshua-zinsser/"
        target="_blank"
        rounded
        outline
        class="linkButton"
        icon="fa-brands fa-linkedin"
      />
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
