<script setup lang="ts">
// const value = ref(50);
// const value2 = ref(true);

// definePageMeta({
//   middleware: "auth",
// });

useHead({
  title: "DreamBuddy - Turn Your Dreams Into Reality",
  meta: [
    {
      name: "description",
      content:
        "Track your savings goals, share with the community, and turn your dreams into reality. Join thousands of users saving smarter with DreamBuddy.",
    },
  ],
});
</script>

<template>
  <!-- <UButton color="success" variant="subtle">Button</UButton>
  <USlider v-model="value" />
  <USwitch v-model="value2" /> -->

  <div>
    <!-- Hero Section -->
    <LandingHero />

    <!-- Feature Section -->
    <LandingFeature />

    <!-- How It Works Section -->
    <LandingHowitwork />

    <!-- Community Section -->
    <LandingComunity />

    <!-- Testimonials Section -->
    <LandingTestimonials />

    <!-- CTA Section -->
    <LandingCTA />
  </div>
</template>
