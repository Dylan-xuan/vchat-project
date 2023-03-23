<template>
  <div class="main">
      <div class="header">
          <div class="container">
                <div class="conetent">
                    <div>
                        <img src="@/assets/1.png"/>
                    </div>
                    <div class="contetnchild">
                        <div class="title1">私密聊天</div>
                        <div class="title2">
                            消息阅后即焚<br/>
                            消息不会被保留在任何设备上<br/>
                            禁止复制或转发消息<br/>
                            头像马赛克防止被截图
                        </div>
                    </div>
                </div>
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
.header{
  width: 100%;
  background-color: #e1d8ff;
  background-size: 100% 100%;
  .container{
    width: 1760px;
    margin: 0 auto;
    padding-top: 194px;
    .conetent{
        padding-left: 88px;
        display: flex;
        justify-content: space-between;
        padding-right: 362px;
        .contetnchild{
            padding-top: 227px;
            .title1{
                font-family: FZLTDHK--GBK1-0;
                font-size: 71px;
                font-weight: normal;
                font-stretch: normal;
                letter-spacing: -4px;
                color: #8c43ef;
            }
            .title2{
                margin-top: 26px;
                font-family: FZLTXHK--GBK1-0;
                font-size: 26px;
                font-weight: normal;
                // font-stretch: normal;
                color: #381e10;
            }
        }
        img{
          width: 614px;
          height: 885px;
        }
    }
  }
}
</style>
