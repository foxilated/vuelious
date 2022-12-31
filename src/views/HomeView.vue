<script setup lang="ts"></script>

<template>
  <main class="flex flex-col gap-8 items-center justify-center">
    <img
      class="w-32"
      src="@/assets/images/logo.svg"
      alt="" />
    <div
      class="flex items-center flex-col justify-center gap-4 text-slate-900 font-light">
      <h1 class="text-5xl animate-pulse">Coming Soon</h1>
      <h2 class="text-lg">Something great is in the works!</h2>
    </div>

    <div
      class="flex flex-col gap-2 absolute bottom-8 left-8 text-slate-900 font-light">
      <div class="flex items-center gap-2">
        <PhMapPin class="w-6 h-6" />
        <a>Iraq, Baghdad, Al-Mansour</a>
      </div>
      <div class="flex items-center gap-2">
        <PhEnvelopeSimple class="w-6 h-6" />
        <a href="mailto:info@digital-logic.tech">info@digital-logic.tech</a>
      </div>

      <div class="flex items-center gap-2">
        <PhPhone class="w-6 h-6" />

        <div class="flex items-center gap-4">
          <a href="tel:+9647809077777">+964 780 9077 777</a>
          <a href="tel:+9647710000866">+964 771 0000 866</a>
          <a href="tel:+9647810000866">+964 781 0000 866</a>
        </div>
      </div>
    </div>
  </main>
</template>
