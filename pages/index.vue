<template>
  <section class="container" v-cloak>
    <v-app id="inspire">
      <v-main>
        <v-container class="fill-height" fluid>
          <v-row align="center" justify="center">
            <v-col cols="12" sm="8" md="4">
              <LoginForm />
            </v-col>
          </v-row>
        </v-container>
      </v-main>
    </v-app>
  </section>
</template>

<script>
import LoginForm from "~/components/LoginForm.vue";

export default {
  components: {
    LoginForm: LoginForm
  }
};
</script>

<style>
</style>

