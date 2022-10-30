<template>
  <GoogleMap
    api-key="AIzaSyDg-Yz00FrUu3SyEhQ7VkuTCQEMoLe96Eo"
    style="width: 100%; height: 500px"
    :center="center"
    :zoom="15"
  >
    <Marker :options="{ position: center }" />
  </GoogleMap>
</template>

<script setup>
import { GoogleMap, Marker } from 'vue3-google-map';
const center = { lat: -8.942872, lng: 13.179949 };
</script>
