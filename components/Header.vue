<template>
  <v-container class="flex justify-center align-center flex-col text-center p-10 bg-gray-200">
    <h1 class="p-5 text-5xl font-bold">{{ headerPage.title }}</h1>
    <Navigation />
  </v-container>
</template>

<script>
export default {
  props: ['headerPage']
}
</script>
