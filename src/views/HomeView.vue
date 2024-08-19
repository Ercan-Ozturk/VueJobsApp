<script setup>
import Hero from "/src/components/Hero.vue";
import HomeCard from "/src/components/HomeCard.vue";
import JobListings from "/src/components/JobListings.vue";
</script>

<template>
  <Hero title="Test Title" subtitle="Test Subtitle"></Hero>
  <HomeCard></HomeCard>
  <JobListings :limit="3" :showButton="true"></JobListings>
</template>
