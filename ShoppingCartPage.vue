<template>
    <div class='wrap'>
       <section class='container'>
        <h1 class='shopCart'>購物車</h1>
        <div class='rightArea'>
            <ol class='step_list'>
                <ul class='step_mum'>
                    <p class='cart'>購物籃</p>
                </ul>
                <ul class='step_mum'>
                    <p class='cart'>訂單/付款</p>
                </ul>
                <ul class='step_mum'>
                    <p class='cart'>訂單完成</p>
                </ul>
            </ol>
        </div>
       </section>

       <section class='unit_bar'>
        <div class='left'></div>
        <div class='right'></div>
       </section>

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
    width:90%;
    margin-top: 50px;
    margin-left: 50px;
    background-color: aquamarine;
}
.shopCart{
    display:flex;
    justify-content: flex-start;
    align-items: center;
}
.rightArea{
    position:absolute ;
    right:10%;
    top:50px;
    border: 1px solid black;
    
}
.step_list{
    display: flex;
    justify-content: right;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    padding-inline-start: 40px;
    
}
.step_mum{
    font-size: 10px;
    font-weight:700;
    
}
</style>