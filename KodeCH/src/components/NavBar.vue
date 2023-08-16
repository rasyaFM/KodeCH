<template>
    <v-app-bar app color="surface" dark flat class="px-12" elevation="3">
      <v-btn>
        <h1>Kode</h1>
      </v-btn>
    
      <v-spacer></v-spacer>
      <v-btn href="/" class="text-orange"> Home</v-btn>
      <v-btn href="About">About</v-btn>
      <v-btn href="Facility">Facility</v-btn>
      <v-btn href="BookNow"> Book Now</v-btn>
      <v-btn href="ContactUs"> Contact Us</v-btn>
    </v-app-bar>
  </template>
  
  <script>
import router from '@/router';
import About from '@/views/AboutView.vue';
import BookNow from '@/views/BookNowView.vue';
import ContactUs from '@/views/ContactView.vue';
import Facility from '@/views/FacilityView.vue';

  export default {
    methods: {
      scroll(refName) {
        const element = document.getElementById(refName);
        element.scrollIntoView({ behavior: "smooth" });
      }, router
    }, views :{
      About,  ContactUs, BookNow, Facility
    }
  };
  </script>
  
  <style>
  *{
    font-style : normal; 
  }
  </style>