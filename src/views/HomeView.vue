<script setup>
import RoundedBox from '../components/RoundedBox.vue';
import Info from '../components/Info.vue';


</script>

<template>
  <main class="container mx-auto bg-gray-50">
    This is homepage
    <div class="mt-8">
      <RoundedBox />
      <Info>
        <template v-slot:shadow-box>shadow box slot</template>
      </Info>
    </div>
  </main>
</template>
<style>

</style>
