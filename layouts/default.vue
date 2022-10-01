<template>
  <v-app dark>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <Footer></Footer>
  </v-app>
</template>

<script>
import Footer from '~/components/footer.vue';
export default {
  name: "DefaultLayout",
  components: { Footer }
}
</script>
