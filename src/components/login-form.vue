<script setup>
import user_icon from "./icons/user.vue";
import lock_icon from "./icons/lock_icon.vue";
</script>

<template>
  <div class="form">
    <h2>Login</h2>
    <form action="">
      <div class="input-box">
        <label>
        <input type="text" placeholder="UserName" />
        <user_icon class="icon"/>
        </label>
      </div>
      <div class="input-box">
        <label for="">
        <input type="password" placeholder="Password" />
        <lock_icon class="icon"/>
        </label>
      </div>
      <div class="links">
        <span><input type="checkbox" /> Remember me</span>
        <a href="#">Forgot Password?</a>
      </div>
      <button>Login</button>
      <div class="new">
        <span>New User? <a href="#">Create account</a></span>
      </div>
    </form>
  </div>
</template>
