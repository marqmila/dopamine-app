<template>
  <div class="d-flex align-items-center py-4 h-100">
    <LoginForm />
  </div>
</template>

<script>
// @ is an alias to /src
import LoginForm from "@/components/LoginForm.vue";

export default {
  name: "LoginView",
  components: {
    LoginForm,
  },
};
</script>

<style scoped></style>
