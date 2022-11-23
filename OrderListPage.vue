<template>
  <div class="wrap">
    <div class="container">
      <section class="coverSetting">
        <div class="profilePic"></div>
        <div class="profile_name">會員姓名</div>
      </section>
    </div>

    <div class="main_contents">
      <section class="sidebarSetting">
        <div class="side_bar">
          <p class="listItem">會員資料</p>
          <p class="listItem">會員訂單</p>
          <p class="listItem">歷史訂單查詢</p>
          <p class="listItem">追蹤清單</p>
          <p class="listItem">貨到通知</p>
          <p class="listItem">訂閱/取消電子報</p>
        </div>
      </section>
    </div>  
  </div>
</template>

<style scoped>

.wrap {
  /* 網頁內容最大寬度 */
  /* max-width: 1920px; */
  min-width: 1440px;
  overflow: hidden;
  min-height: 100vh;
  /* 測試用 */
  background-color: white;
}
/* 最上面的漸層區塊 */
.container {
  width: 100%;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  background-image: linear-gradient(-5deg, #53929b, #e3d096);
  /*  */
}

.coverSetting {
  width: 100%;
  margin: 0 auto;
  justify-content: flex-start;
}

.coverSetting .profilePic {
  margin-left: 180px;
  margin-top: 10px;
  margin-bottom: 20px;
}
.coverSetting .profile_name {
  margin-left: 200px;
  padding-bottom: 20px;
}
.profilePic {
  width: 100px;
  font-size: 20px;
  border-radius: 50%;
  background-color: rgb(185, 187, 181);
  padding-top: 120px;
  padding-right: 20px;
}
.profile_name {
  color: white;
  font-size: 20px;
  font-weight: bold;
}

/* 左邊sidebar區塊 */
.main_contents {
  display: flex;
  justify-content: flex-start;
}

.main_contents .sidebarSetting {
  margin-left: 200px;
  margin-top: 40px;
}

.side_bar .listItem {
  color: black;
  font-size: 20px;
  font-family: "Genseki-R", Sans-Serif;
}


</style>