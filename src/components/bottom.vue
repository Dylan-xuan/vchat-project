<template>
  <div class="main">
      <div class="div1">
        <div>下载</div>
        <div>功能</div>
        <div>常见问题</div>
        <div>VChat网页版</div>
        <div>最新动态</div>
      </div>
      <div class="line1"></div>
      <div class="div2">
          <div class="download">下载</div>
          <div class="downloadApp">
            <a href="https://apps.apple.com/us/app/vchat/id1658329590" target="_blank">
              <img class="img1" src="@/assets/apple2.png"/>
            </a>
            <a href="https://play.google.com/store/apps/details?id=com.zww.chat" target="_blank">
              <img src="@/assets/Google2.png"/>
            </a>
          </div>
      </div>
      <div class="line2"></div>
      <div class="div3">
          <div class="download">友情链接</div>
          <div class="right">
            <img src="@/assets/iconBrid.png"/>
            <img src="@/assets/iconcam.png"/>
            <img src="@/assets/iconf.png"/>
          </div>
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
  display: flex;
  justify-content: center;
	height: 380px;
  box-sizing: border-box;
	background-color: #1d0c2e;
  padding-top: 85px;
  .div1{
    	width: 160px;
      font-family: FZLTXHK--GBK1-0;
      font-size: 26px;
      font-weight: normal;
      font-stretch: normal;
      line-height: 33px;
      color: #ffffff;
      div{
        margin-bottom: 12px;
      }
  }
  .div2{
    	font-family: FZLTXHK--GBK1-0;
	font-size: 26px;
	font-weight: normal;
	font-stretch: normal;
	line-height: 28px;
	letter-spacing: 0px;
	color: #ffffff;
  img{
    width: 235px;
    height: 69px;
  }
  .download{
    margin-bottom: 27px;
  }
  .downloadApp{
    display: flex;
    img{
      margin-right: 11px;
    }
  }
  }
  .div3{
    	font-family: FZLTXHK--GBK1-0;
      font-size: 26px;
      font-weight: normal;
      font-stretch: normal;
      line-height: 28px;
      letter-spacing: 0px;
      color: #ffffff;
      img{
        width: 103px;
	      height: 104px;
        margin-right: 13px;
      }
      .download{
    margin-bottom: 27px;
      }
      .right{
        display: flex;
        cursor: pointer;
      }
  }
  .line1{
      width: 1px;
      height: 224px;
      background-color: #ffffff;
      margin-left: 64px;
      margin-right: 78px;
  }
  .line2{
      width: 1px;
      height: 224px;
      background-color: #ffffff;
      margin-left: 78px;
      margin-right: 45px;
  }
}
</style>
