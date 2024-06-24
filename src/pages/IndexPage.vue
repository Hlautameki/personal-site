<template>
  <q-page class="flex justify-center bg-black" bg-color="black">

    <img
      v-if="false"
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
    <q-card class="bg-black text-white q-mt-xl">
      <q-card-section class="flex justify-center">
        <q-avatar
          size="150px"
        >
          <q-img
            src="IMG_1365.jpeg"
          />
        </q-avatar>
      </q-card-section>
      <q-card-section class="flex justify-center">
        <div
          class="text-weight-medium"
          :class="$q.screen.lt.sm ? 'text-h3' : 'text-h2'"
        >
          Hi, I'm Mateusz
        </div>
      </q-card-section>
      <q-card-section class="text-grey-4 flex justify-center q-pt-none">
        <div class="text-weight-light" style="font-size: 1.4rem">I'm full stack software developer</div>
      </q-card-section>
      <q-card-section class="flex justify-center q-gutter-md">
        <q-btn round color="white" href="http://www.google.com" target="_blank" size="md">
          <q-icon class="text-black" name="fa-brands fa-linkedin" />
        </q-btn>
        <q-btn round color="white" href="http://www.google.com" target="_blank" size="md">
          <q-icon class="text-black" name="fas fa-envelope"/>
        </q-btn>
        <q-btn round color="white" href="http://www.google.com" target="_blank" size="md">
          <q-icon class="text-black" name="fa-brands fa-facebook"/>
        </q-btn>
        <q-btn round color="white" href="http://www.google.com" target="_blank" size="md">
          <q-icon class="text-black" name="fa-brands fa-twitter"/>
        </q-btn>
      </q-card-section>
    </q-card>
  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});

import { useQuasar} from "quasar"

const $q = useQuasar();

</script>
