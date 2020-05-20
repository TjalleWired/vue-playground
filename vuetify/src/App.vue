<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Wiredworkers Logo"
          class="shrink mr-2"
          contain
          src="https://wiredworkers.io/wp-content/uploads/2018/01/cropped-wiredworkers-logo-white-50x40.png"
          transition="scale-transition"
          width="40"
        />

        <h2>Wiredworkers</h2>
      </div>

      <v-spacer></v-spacer>

      
     
    </v-app-bar>

    <v-content>
      <LoginForm/>
    </v-content>
  </v-app>
</template>

<script>
import LoginForm from './components/LoginForm';

export default {
  name: 'App',

  components: {
    LoginForm,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
h2 {
  font-family: Arial, Helvetica, sans-serif;
  font-weight: lighter;
}
</style>