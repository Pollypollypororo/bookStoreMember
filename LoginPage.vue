

<template>
  <div class="container">
    <form class="userLogin">
      <h3>已經是書店的會員了?</h3>

      <div class="form-group">
        <input type="email" class="form-control" placeholder="請輸入您的ID" />
      </div>

      <br />

      <div class="form-group">
        <input
          type="password"
          class="form-control form-control-lg"
          placeholder="請輸入您的密碼"
        />
      </div>

      
      <br />

      <button type="submit" class="login_btn">登入</button>
      <br />
      <br />

      <button class="register_btn">
        <router-link to="/register"> 註冊 </router-link>
      </button>

      <br />
      <br />

      <p class="forgot-password text-right mt-2 mb-4">
        <router-link to="/forgot-password">忘記密碼?</router-link>
      </p>
    </form>
  </div>
</template>

<script>
// export default {
//   data:{
//     return: {
//       imgUrl: "./src/assets/bookStore_logo.png"
//     }
//   }
// }
</script>


<style scoped>
.container {
  width: 100%;
  margin:auto;
  text-align: center;
}

.form-control {
  display: inline-block;
  padding: 0 14px 2px;
  font-size: 14px;
  letter-spacing: 0em;
  border: 1px solid #d5d5d5;
  border-radius: 6px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-size: 10px;
}
.form-group input {
  width: 250px;
  height: 30px;
}

.login_btn {
  color:white;
  background: #5055b1;
  border: 1px solid #5055b1; 
  width:250px;
  height:30px;
  border-radius: 6px;
}

.register_btn{

  color:#5055b1;
  background: white;
  border: 1px solid #5055b1; 
  width:250px;
  height:30px;
  border-radius: 6px;

}
</style>