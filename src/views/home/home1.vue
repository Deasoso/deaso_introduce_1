<template>
  <div>
    <div class="cardcontainer">
      <div class="fullwidth">
        <div class="columns is-gapless">
          <div class="column fullheight">
            <div class="vermiddle">
              <img class="avatar" src="http://chairimg.deaso40.com/background/touxiang2.jpg"/>
              <h1 class="title whiteborder">
                四零
              </h1>
              <h2 class="subtitle whiteborder">
                呀，居然真的扫进来了！
              </h2>
            </div>
          </div>
          <div class="column fullheight">
            <div class="vermiddle">
              <div class="whiteback">
                <h2 class="subtitle blackfont">
                  cn四零 长沙 INFJ<br>
                  <br>
                  oc人 独立游戏 微cos<br>
                  我玩：第五 金铲铲 雀魂 使命手游<br>
                  第五人格：先知，隐囚<br>
                  东方：文文，主角组<br>
                  番喜欢智斗：噬谎者，死笔，斗牌传说，赌博默示录<br>
                  <br>
                  b站建站玩家。游戏LOL，CSGO，无畏契约样样不落。<br>
                  自从接触上了第五人格以上游戏都失去了乐趣。<br>
                  想玩请直接找我开黑。<br>
                  <br>
                  基本无雷好相处，不拒同担。<br>
                  消息基本秒回，没回就是在睡觉。<br>
                  主播体质，熟了之后很能整活。<br>
                  成分极其复杂介绍不完，熟悉后可慢慢解锁。<br>
                  <br>
                  联系方式点点右上角就好啦。
                </h2>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    methods: {
      toMe() {
        document.getElementById('introduceme').scrollIntoView({ block: 'start', behavior: 'smooth' })
      },
      toGame(){
        this.$router.push("/games");
      },
      toMusic(){
        this.$router.push("/musics");
      },
      clickDownload(){
        this.$buefy.dialog.alert({
          title: '跳转',
          message: '<div>链接：</div><a href="https://www.tapechat.net/uu/90ZYPL/3XWRGVSM" target="_blank">https://www.tapechat.net/uu/90ZYPL/3XWRGVSM</a>',
          confirmText: '关闭'
        })
      }
    }
  }
</script>

<style scoped>
/*
  section 2
*/
.avatar{
  height: 132px;
  width: 132px;
  border-radius:50%;
  border: 3px solid white;
  vertical-align: top;
  display:inline-block;
  margin-bottom: 20px;
}
.cardcontainer{
  background-image: url("http://chairimg.deaso40.com/background/manread.jpg");
  background-size: cover;
  background-position: 50% 50%;
}
.whiteborder{
  text-shadow:5px 2px 6px #000000;
  color: #ffffff
}
.fullheight{
  height: 800px;
}
.fullwidth{
  max-width: 1280px;
  margin: auto;
}
.vermiddle{
  position: relative;
  top: 50%;
  transform: translateY(-50%);
}
.whiteback{
  margin-left: 30px;
  margin-right: 30px;
  padding: 30px;
  height: 620px;
  background-color: #ffffffbb;
  text-align: left;
}
.blackfont{
  color: #000000;
}

</style>