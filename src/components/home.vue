<template>
  <div class="main">
      <div class="header">
          <div class="container">
            <div class="m_c">
              <div class="child_left">
                  <div class="lefttext"> 即时通讯，不止于此</div>
                  <div class="lefttext1"> 沉浸式的社交体验，保障社交信息安全</div>
                  <div class="container_left">
                      <div>
                        <a href="https://apps.apple.com/us/app/vchat/id1658329590"  target="_blank">
                        <img class="img1" src="@/assets/Apple.png"/>
                        </a>
                        Apple APP Store
                      </div>
                      <div>
                        <a href="https://play.google.com/store/apps/details?id=com.zww.chat"  target="_blank" >
                          <img class="img2" src="@/assets/Google.png"/>
                        </a>
                        Google play Store
                      </div>
                  </div>
                  <div class="headerB">
                      <div>
                        下载会覆盖原app，需要保留历史记录的用户，请在原
                        app内先备份聊天记录之后，在下载更新app后恢复聊
                        天记录。
                      </div>
                      <div class="bottom">
                        “我的”- >“通用”- > “聊天记录备份”
                      </div>
                  </div>
              </div>
              <div class="child_right">
                <div>
                  <img src="@/assets/iPhone.png"/>
                </div>
              </div>
            </div>
            <div class="vchat">
              <img src="@/assets/icon.png"/>
              VChat
            </div>
          </div>
      </div>
      <div>
        <contentTo></contentTo>
      </div>
      <div>
        <contentThree></contentThree>
      </div>
      <div>
        <bottom></bottom>
      </div>
  </div>
</template>

<script>
import contentTo from './contentTo.vue'
import contentThree from './contentThree.vue'
import bottom from './bottom.vue'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    contentTo,contentThree,bottom
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less" >
.main{
  width: 100%;
}
.header{
  width: 100%;
  height: 1083px;
  background: url('~@/assets/bg1.png');
  background-repeat: no-repeat;
  background-size: cover;
  .container{
    width: 1760px;
    margin: 0 auto;
    padding-top: 107px;
    .lefttext{
      font-family: FZLTDHK--GBK1-0;
      font-size: 71px;
      font-weight: normal;
      font-stretch: normal;
      letter-spacing: -4px;
      color: #ffffff;
    }
    .lefttext1{
      font-family: FZLTXHK--GBK1-0;
      font-size: 33px;
      font-weight: normal;
      font-stretch: normal;
      color: #ffffff;
    }
    .container_left{
      display: flex;
      >div{
        margin-top: 124px;
        display: flex;
        flex-direction: column;
        align-items: center;
        font-family: FZLTXHK--GBK1-0;
        font-size: 28px;
        font-weight: normal;
        font-stretch: normal;
        color: #ffffff;
        img{
          margin-bottom: 34px;
          margin-right: 13px;
        }
      }
    }
    .headerB{
        width: 609px;
        font-family: FZLTXHK--GBK1-0;
        font-size: 26px;
        font-weight: normal;
        font-stretch: normal;
        color: #ffffff;
        margin-top: 106px;
        .bottom{
          margin-top: 70px;
        }
    }
    .m_c{
      display: flex;
      justify-content: space-between;
      .child_left{
        padding-top: 105px;  
      }
    }
    .child_right{
      img{
        width: 978px;
        height: 945px;
      }
    }
    .vchat{
        display: flex;
        align-items: center;
        font-family: FZCSK--GBK1-0;
        font-size: 65px;
        font-weight: normal;
        font-stretch: normal;
        color: #fefefe;
        position: absolute;
        top: 58px;
        img{
          margin-right: 24px;
        }
    }
  }
}
</style>
