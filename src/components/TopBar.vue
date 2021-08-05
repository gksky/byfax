<template>
  <div class="topBar">
    <div class="auth">
      <button class="login">Вход</button>
      <button class="register">Регистрация</button>
      <select class="lang">
        <option>ENG</option>
        <option>РУС</option>
        <option>БЕЛ</option>
      </select>
    </div>
  </div>
</template>

<script>

export default {
  name: 'TopBar',
}
</script>

<style>
.topBar {
  
  background-color: #012c3d;
}
.auth {
  margin: 0 auto;
  max-width: 1100px;
}
button.login {
  background-color: #769201;
  color: #ffffff;
}
button.register {
  background-color: #005e78;
  color: #ffffff;
}
</style>