<template>
  <q-layout view="hHh lpr fFf">
    <q-header reveal class="customHeader" height-hint="98">
      <q-toolbar>
        <q-avatar>
          <img class="logo" src="../assets/logo-white.svg" />
        </q-avatar>
        <q-space />
        <q-tabs stretch align="justify">
          <q-route-tab to="/" icon="fa-solid fa-house-chimney" label="home" />
          <q-route-tab
            to="/email"
            icon="fa-solid fa-envelopes-bulk"
            label="email"
          />
          <q-route-tab
            to="/websites"
            icon="fa-solid fa-globe"
            label="websites"
          />
        </q-tabs>
        <q-space />
        <q-btn
          rounded
          outline
          @click="$q.dark.toggle()"
          class="dmToggle"
          icon="fa-solid fa-lightbulb"
        />
      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
    <q-footer>
      <q-toolbar class="row no-wrap justify-center content-around">
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
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script>
import { ref } from "vue";
import { useQuasar } from "quasar";

export default {
  setup() {
    const $q = useQuasar();
  },
};
</script>
