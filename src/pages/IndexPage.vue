<template>
  <q-page class="flex flex-center bg-black" bg-color="black">

    <img
      v-if="false"
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
    <q-card class="bg-black text-white">
      <q-card-section class="flex justify-center">
        <q-avatar
          size="150px"
        >
          <q-img
            src="IMG_1365.jpeg"
          />
        </q-avatar>
      </q-card-section>
      <q-card-section>
        <div class="text-h2 text-weight-medium">Hi, I'm Mateusz</div>
      </q-card-section>
    </q-card>
  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>
