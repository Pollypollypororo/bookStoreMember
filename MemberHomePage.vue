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

      <div class="main_box">
        <section class="mainbox_inner">
          <h1>會員資料設定</h1>
          <h3>會員資料</h3>
          <hr />
          <div class="inner_title">
            帳號 / ID
            <div class="inner_contents">
              <span>example@gmail.com</span>
            </div>
          </div>
          <br />
          <div class="inner_title">
            修改密碼 / 新密碼
           <input class="inner_contents" type="text" placeholder="請重新輸入密碼" /> 
          </div>

          <span class="notice"
            >*至少八個字符,
            包含大小寫英文字母、數字或特殊符號，不允許使用連續或重複的三個字節</span
          >

          <br />

          <div class="inner_title_wrap">
            <div class="inner_title">姓名 
              <span class="inner_contents">小丸子 </span>
              <div class="inner_btn">
              <button class="btn_change">變更</button>
            </div>
            </div>
           
            
          </div>

          <br />

          <div class="inner_title_wrap">
            <div class="inner_title">出生日期
              <span class="inner_contents">1988.1.12</span>
            </div>
            
          </div>

          <br />

          <div class="inner_title_wrap">
            <div class="inner_title">電子郵件
              <span class="inner_contents">example@gmail.com</span>
              <div class="inner_btn">
              <button class="btn_change">變更</button>
            </div>
            </div>
            
           
          </div>

          <br />

          <div class="inner_title_wrap">
            <div class="inner_title">手機號碼
              <span class="inner_contents">0988523645</span>
              <div class="inner_btn">
              <button class="btn_change">變更</button>
            </div>
            </div>
          
            
          </div>

          <hr />
          <div class="btn_setting">
            <button class="btn_grey_clear">清除</button>&nbsp;
            <button class="btn_blue_confirm">確認</button>
          </div>
        </section>
      </div>
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

/* 中間會員資料區塊 */
.main_contents .main_box {
  display: inline-flex;
  margin-left: 50px;
  margin-top: 20px;
  justify-content: center;
  width: 60%;
  /* border: 4px solid lightsalmon; */
}
.mainbox_inner {
  display: inline;
  vertical-align: inherit;
  width: 100%;
}
.notice {
  display: block;
  justify-content: flex-start;
  font-size: xx-small;
  color: brown;
}
.mainbox_inner .inner_title {
  display: inline;
  line-height: 40px;
  font-size: 10px;
  font-weight: bold;
  width: 100%;
}
.btn_change {
  color: var(--primary-color);
  background: white;
  border: 1px solid var(--primary-color);
  width: 50px;
  height: 25px;
  border-radius: 6px;

}
.mainbox_inner.inner_title_wrap .inner_title {
  align-content: center;
}
.inner_contents{
  display:inline-block;
  margin-inline: 100px;
  margin-left: 100px;
  text-align: left;
  
  
}

.inner_btn{
  display: flex;
  justify-content: right;
  margin-right:500px
  
}
.btn_grey_clear {
  color: white;
  background: var(--neutral-color);
  border: 1px solid var(--neutral-color);
  width: 250px;
  height: 30px;
  border-radius: 6px;
}

.btn_blue_confirm {
  color: white;
  background: var(--primary-color);
  border: 1px solid var(--primary-color);
  width: 250px;
  height: 30px;
  border-radius: 6px;
}
.btn_setting {
  margin-top: 20px;
  margin-bottom: 20px;
  padding-inline-start: 200px;
}
</style>