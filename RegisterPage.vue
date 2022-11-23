<template>
<div class="wrap">
<main class="container">
    <section class="contents">
        
        <div class="title_wrap">
            <h1 class="title_heading">註冊電子郵件</h1>
        </div>
        <hr>
        <div class=content_inner>
        <div class="info_inner">
            <h2>請輸入您的會員資訊</h2>
            <div class="for_wraping_title">
            <span class="words_setting">ID *</span>
            </div>
           
            <div class="for_wraping">
            <input class="inputInner" type="text" placeholder="請輸入郵件">
            </div>
            <div class="for_wraping_title">
            <input type="checkbox">將電子郵件作為ID 
            </div>
            <div class="for_wraping_title">
            <span class="words_setting">密碼*</span>
            </div>
            <div class="for_wraping">
            <input class="inputInner" type="text" placeholder="請輸入密碼">
            </div>
            <div class="for_wraping_title">
            <span class="sml_word">英文、數字和特殊字母三種組合8位字符，不允許使用空格和三個連續字元或重複字元</span>
            </div>
            <div class="for_wraping_title">
            <span class="words_setting">驗證密碼</span>
            </div>

            <div class="for_wraping">
            <input class="inputInner" type="text" placeholder="請再輸入一次密碼">
            </div>
            <div class="for_wraping_title">
            <span class="words_setting">姓名*</span>
            </div>
            <div class="for_wraping">
            <input class="inputInner" type="text" placeholder="請輸入您的大名">
            </div>
            <div class="for_wraping_title">
            <span class="words_setting">手機號碼*</span>
            </div>
            <div class="for_wraping">
            <input class="inputInner" type="text" maxlength="10" placeholder="請輸入電話號碼">
            </div>
            <div class="for_wraping_title">
            <span class="words_setting">電子郵件*</span>
            </div>
            <div class="for_wraping">
            <input class="inputInner" type="email" placeholder="請輸入電子郵件">
            </div>
            <div class="for_wraping_title">
            <span class="words_setting">生日*</span>
            </div>
            <div class="for_wraping">
            <input class="inputInner" type="text" maxlength="8" placeholder="請輸入您的生日八位數">
           </div>
        <br><br>
        <div class="for_wraping">
        <button class="register_btn">註冊會員</button>
        </div>
        </div>
        </div>
        

       

    </section>
</main>
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
.container{
  width: 100%;
  margin: 0 auto;
  margin-bottom:100px;
  display: flex;
  justify-content: center;
  /* background-color: lightblue; */
  align-content: center;
  flex-wrap: wrap;
}
.contents{
    width:70%;

}
.title_wrap{
    display: flex;
    justify-content: center;
}
h1 {
    font-size: 2.375rem;
    /* 38px */
    line-height: 55px;
    font-family: 'Genseki-H';
    
}
h2 {
    color:#2E2A39;
    font-size: 1.875rem;
    /* 30px */
    line-height: 40px;
    font-family: 'Genseki-B';
    text-align: center;
}



.content_inner{
    display:flex;
    align-content: center;
    justify-content: center;
    flex-wrap: wrap;
 
}
.info_inner{
    display: block;
    
}



.words_setting {
    display:flex;
    justify-content: left;
    font-size: 10px;
    /* 16px */
    font-family: 'Genseki-R';
    color:#2E2A39;
    padding:10px 0 0px 0;
    letter-spacing: -0.01em;
    height:10px;
}
.sml_word{
    display: inline-flex;
    font-size: 2px;
    padding:5px 0 5px 0;;
    text-align:left;
    color:#FD9301;
}
.inputInner{
  display: inline-block;
  padding: 5px 0 5px 2px;;
  font-size: 14px;
  letter-spacing: -0.01em;
  border: 1px solid #d5d5d5;
  border-radius: 6px;
  font-size: 10px;
  width: 300px;
  height: 20px;
}
 .register_btn{
position: relative;
justify-content: center;
  color:#53929B;
  background: white;
  border: 1px solid #53929B; 
  width:250px;
  height:30px;
  border-radius: 6px;

}
.for_wraping{
    display:flex;
    justify-content: center;
}
.for_wraping_title{
    display:block;
    margin-left: 150px;
    margin-bottom: 10px;
    padding-top:4px;
}
</style>