<template>
  <div class="container">
    <div class="box">
      <div class="img">
        <img src="./icos/录制.png"/>
      </div>
      <p>录音机</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/微信.png"/>
      </div>
      <p>微信</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/日历.png"/>
      </div>
      <p>日历</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/时钟.png"/>
      </div>
      <p>时钟</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/浏览器.png"/>
      </div>
      <p>浏览器</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/电话.png"/>
      </div>
      <p>电话</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/相册.png"/>
      </div>
      <p>相册</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/相机.png"/>
      </div>
      <p>相机</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/短信.png"/>
      </div>
      <p>短信</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/通讯录.png"/>
      </div>
      <p>通讯录</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/youtube.png"/>
      </div>
      <p>Youtube</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/facebook.png"/>
      </div>
      <p>Facebook</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/BILIBILI_LOGO.png"/>
      </div>
      <p>哔哩哔哩动画</p>
    </div>
    <div class="box">
      <div class="img">
        <img src="./icos/QQ.png"/>
      </div>
      <p>QQ</p>
    </div>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #efeeee;
}

.container {
  width: 700px;
  height: 600px;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-items: center;
}

.container .box {
  display: flex;
  justify-content: space-around;
  flex-direction: column;
  align-items: center;
  align-content: center;
  width: 100px;
  height: 140px;
  margin: 20px;
}

.container .box .img {
  width: 100px;
  height: 100px;
  box-shadow: 18px 18px 30px rgba(0, 0, 0, 0.1),
  -18px -18px 30px rgba(255, 255, 255, 1);
  border-radius: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #efeeee;
  transition: box-shadow .2s ease-out;
  position: relative;
}

.container .box .img img {
  width: 60px;
  transition: width 0.2s ease-out;
}

.container .box p {
  color: slategrey;
}

.container .box .img:hover {
  box-shadow: 0px 0px 0px rgba(0, 0, 0, 0.2),
  0px 0px 0px rgba(255, 255, 255, 0.8),
  inset 18px 18px 30px rgba(0, 0, 0, 0.1),
  inset -18px -18px 30px rgba(255, 255, 255, 1);
  transition: box-shadow .2s ease-out;
}

.container .box .img:hover img {
  width: 58px;
  transition: width 0.2s ease-out;
}

</style>