<template>
  <div class="logon-container">
    <section class="form">
      <img src="../assets/logo.png" />

      <form>
        <h1>Faça seu logon</h1>

        <input placeholder="Sua ID" />
        <button class="button" type="submit">Entrar</button>
        <router-link class="back-link" to="/register"
          >Não tenho cadastro</router-link
        >
      </form>
    </section>
    <img src="../assets/heroes-green.jpg" alt="Heroes" />
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>

<style>
.logon-container {
  width: 100%;
  max-width: 1120px;
  height: 100vh;
  margin: 0 auto;

  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logon-container section.form {
  width: 100%;
  max-width: 350px;
  margin-right: 30px;
}

.logon-container section.form form {
  margin-top: 100px;
}

.logon-container section.form form h1 {
  font-size: 32px;
  margin-bottom: 32px;
}

.back-link:hover {
  color: var(--main-color);
}
</style>
