<template>
  <div class="main">
      <div class="container">
        <div class="text1">语音视频聊天</div>
        <div class="text">
          <span>畅所欲言</span><br/>
        语音通话让您与身在国外的家人和朋友免费通话，
        而免费的视频通话更可以在您无法以文字和声音完
        全表达意思时让您面对面的与对方聊天。 VChat 语
        音和视频通话使用的是手机的网络连接，而不是运
        营商计划通话分钟，这样您就不用担心昂贵的电话
        费用了。"
        </div>
      </div>
       <div class="img3">
          <img  src="@/assets/iPhone3.png"/>
        </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less" >
.main{
  width: 100%;
  height: 1083px;
  position: relative;
   background: url('~@/assets/bg2.png');
   background-size: 100% 100%;
   background-repeat: no-repeat;
   .container{
    width: 1760px;
    padding-left: 101px;
    margin: 0 auto;
    padding-top: 226px;
    .text1{
      font-family: FZLTDHK--GBK1-0;
      font-size: 71px;
      font-weight: normal;
      // font-stretch: normal;
      color: #8c43ef;
      margin-bottom: 26px;
    }
    .text{
      	width: 573px;
       	font-family: FZLTXHK--GBK1-0;
        font-size: 26px;
        font-weight: normal;
        color: #381e10;
    }
   }
    .img3{
      position: absolute;
      right: 0;
      bottom: 0;
      img{
        width: 1305px;
        height: 921px;
      }
    }
}
</style>
