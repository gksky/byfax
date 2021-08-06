<template>
  <div class="topBar">
    <div class="auth">
      <div class="social">
        fdsgdg
      </div>
      <div>
        <button class="login">Вход</button>
        <button class="register">Регистрация</button>
        <select class="lang">
          <option>ENG</option>
          <option>РУС</option>
          <option>БЕЛ</option>
        </select>
      </div>
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
  height: 50px;
  background-color: #012c3d;
  
}
.social {
  display: none;
}
.auth {
  margin: 0 auto;
  max-width: 1100px;
  height: 100%;
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
}
button {
  font-size: 14px;
  min-height: 30px;
  text-transform: uppercase;
  padding: 5px 8px;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-width: 0;
  border-radius: 4px;
  text-align: center;
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