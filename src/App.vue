<template>
  <div class="container">
    <Default>
      <h1>Slot par défaut</h1>
    </Default>

    <Named>
      <template v-slot:title>
        <h1>Slot nommé</h1>
      </template>
      <template v-slot:content>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minima repellat vitae, in animi harum alias!
          Magninatus enim numquam perspiciatis deleniti. Sunt dolorum odit, pariatur impedit dolor ullam voluptatibus
          laborum?
        </p>
      </template>
    </Named>
  </div>
</template>

<script setup>
import Default from "./components/Default.vue"
import Named from "./components/Named.vue"
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  align-items: center;
}
</style>
