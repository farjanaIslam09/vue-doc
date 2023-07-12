<template>
    <div>
        <ShadowBox>
        <template v-slot="">
          <slot name="shadow-box">
            
          </slot>
        </template>
      </ShadowBox>
    </div>
</template>

<script setup>
import ShadowBox from './ShadowBox.vue';


</script>

<style scoped>

</style>