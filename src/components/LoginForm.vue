<template>
  <main class="w-100 m-auto form-container">
    <form>
      <h1 class="dopamineTitle h1 mb-3">Dopamine</h1>
      <img
        class="mb-4"
        alt="Dopamine logo"
        src="../assets/dopamine-logo.png"
        height="70"
        width="150"
      />
      <div class="form-floating mb-3">
        <input
          type="text"
          class="form-control"
          id="floatingInput"
          placeholder="Username"
          aria-label="Username"
          focus-ring
        />
        <label for="floatingInput">Username</label>
      </div>
      <div class="form-floating mb-3">
        <input
          type="password"
          class="form-control"
          id="floatingPassword"
          placeholder="Password"
          aria-label="Password"
        />
        <label for="floatingPassword">Password</label>
      </div>
      <button type="submit" class="btn w-100 py-2">Sign in</button>
    </form>
  </main>
</template>

<script>
export default {
  name: "LoginForm",
};
</script>

<style scoped>
.form-container {
  max-width: 400px;
  padding: 1rem;
  color: #b6bbc4;
}

.form-control:focus {
  border-color: #b6bbc4;
  box-shadow: 0 0 0 0.2rem #424769;
}

.dopamineTitle {
  font-family: "Lato", sans-serif;
  font-weight: 300;
  font-style: italic;
}

.form-floating {
  font-weight: 300;
  font-style: normal;
}

.btn {
  font-weight: 300;
  font-style: normal;
  background-color: #424769;
}
.btn:hover {
  background-color: #b6bbc4;
  color: #424769;
}
</style>
