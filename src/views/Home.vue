<template>
  <div class="profile-container">
    <header>
      <img src="../assets/logo.png" alt="Be the Hero" />
      <span>Bem vindo, APAD</span>

      <router-link class="button" to="/incidents/new"
        >Cadastrar novo caso</router-link
      >
      <button type="button"><v-icon name="eye"></v-icon></button>
    </header>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
.profile-container {
  width: 100%;
  max-width: 1180px;
  padding: 0 30px;
  margin: 32px auto;
}

.profile-container header {
  display: flex;
  align-items: center;
}

.profile-container header span {
  font-size: 20px;
  margin-left: 24px;
}

.profile-container header img {
  height: 64px;
}

.profile-container header a {
  width: 260px;
  margin-left: auto;
  margin-top: 0;
}
</style>
