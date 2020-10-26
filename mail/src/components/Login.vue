<template>
  <div class="loginOutter">
    <h1>Campus mall登录系统</h1>
    <div class="loginInner">
      <div class="liLeft">
        <div class="liLeftMid">
          <h2>Welcome to Campus Mall !</h2>
          <p>奔跑吧骄傲的少年</p>
          <p>年轻的心里面是坚定的信念</p>
          <p>燃烧吧骄傲的热血</p>
          <p>胜利的歌我要再唱一遍</p>
          <p>奔跑吧</p>
          <p>奔跑吧</p>
          <p>...</p>
          <p>
            摘自：<a
              href="https://music.163.com/#/song?id=408332757&market=baiduqk"
              target="_blank"
              >骄傲的少年（南征北战NZBZ）</a
            >
          </p>
        </div>
      </div>
      <div class="liRight">
        <div class="liRightMid">
          <form class="loginForm">
            <p>
              <span class="formSpan"> 账号：</span
              ><input class="formInput" type="text" placeholder="用户名/账号" />
            </p>
            <p>
              <span class="formSpan"> 密码：</span
              ><input class="formInput" type="text" placeholder="密码" />
            </p>
            <p>
              下次是否自动登录：<input
                type="radio"
                id="loginYes"
                name="autoLogin"
              />
              <label for="loginYes">是</label
              ><input type="radio" id="loginNo" name="autoLogin" />
              <label for="loginNo">否</label>
            </p>
            <p style="text-align: center">
              <input class="formSubmit" type="submit" value="登  录" />
            </p>
            <p class="formbut">
              <a class="formForget" href="#">忘记密码？</a
              ><a
                id="Register"
                class="Register"
                href="./Register.html"
                target="_blank"
                >注册新用户</a
              >
            </p>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {

};
</script>


<style scoped>
html {
  overflow: hidden;
}
.loginOutter {
  width: 100%;
  height: 600px;
  position: relative;
}
h1 {
  text-align: center;
  color: slateblue;
}
h2 {
  color: #6f95c8;
}
.loginInner {
  width: 80%;
  height: 80%;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  background-image: url(../assets/lian.jpg);
}
.liLeft {
  width: 60%;
  height: 100%;
  position: absolute;
  left: 0;
}
.liLeftMid {
  width: 80%;
  height: 80%;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
.liLeftMid p {
  font-weight: bold;
}
.liRight {
  width: 40%;
  height: 100%;
  position: absolute;
  right: 0;
}
.liRightMid {
  width: 80%;
  height: 60%;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
.formSpan {
  font-weight: bold;
  font-size: 22px;
}
.formInput {
  width: 70%;
  height: 40px;
  border-radius: 5px;
  border-width: 2px;
  border-color: #6f95c8;
  font-size: 22px;
}
.formSubmit {
  width: 65%;
  height: 40px;
  border: 0;
  border-radius: 5px;
  background-color: #5a98de;
  font-size: 22px;
  color: white;
}

.formForget {
  position: absolute;
  left: 10px;
  bottom: 5px;
  text-decoration: none;
  color: #6f95c8;
}
.Register {
  position: absolute;
  right: 10px;
  bottom: 5px;
  text-decoration: none;
  color: #6f95c8;
}
</style>