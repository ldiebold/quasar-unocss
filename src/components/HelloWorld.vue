<script setup>
const form = ref({
  name: '',
  email: ''
})
</script>

<template>
  <q-card p="y-8 x-4">
    <q-card-section mt-7>
      <q-input filled label="name" v-model="form.name"></q-input>
      <q-input filled label="email" v-model="form.email"></q-input>
    </q-card-section>
  </q-card>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
