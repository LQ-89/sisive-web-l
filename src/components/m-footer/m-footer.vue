<template>
  <div class="container">
    <div class="foot">
      <div class="foot-item">
        <div class="left">
          <div class="plate" style="background-image: url(static/image/sisivc/foot/address@4x.png);">
            <h3>地址</h3>
            <p>中国·上海市徐汇区复兴中路1380号</p>
          </div>
          <div class="plate" style="background-image: url(static/image/sisivc/foot/email@4x.png);margin-top:40px;">
            <h3>邮箱</h3>
            <p>adminoffice@Competition.com</p>
          </div>
        </div>
        <div class="center plate" style="background-image: url(static/image/sisivc/foot/subway@4x.png);">
          <h3>地铁</h3>
          <ul>
            <li>
              <img src="static/image/sisivc/foot/1@4x.png">
              <p>1号线</p>
              <p>常熟路站 </p>
              <p>4号口</p>
            </li>        
            <li>
              <img src="static/image/sisivc/foot/7@4x.png">
              <p>7号线 </p>
              <p>常熟路站 </p>
              <p>6/7号口</p>
            </li>
            <li>
              <img src="static/image/sisivc/foot/10@4x.png">
              <p>10号线 </p>
              <p>陕西南路站</p>
              <p>7号口</p>
            </li>        
            <li>
              <img src="static/image/sisivc/foot/12@4x.png">
              <p>12号线 </p>
              <p>陕西南路站 </p>
              <p>7号口</p>
            </li>
          </ul>
        </div>
        <div class="right" style="padding-left:60px">
          <div class="plate" style="background-image: url(static/image/sisivc/foot/bus@4x.png);">
            <h3>公交</h3>
            <p>15/26/42/45/49/96/167/198/315/320<br>327/824/830/911/920/926/927</p>
          </div>
        </div>
      </div>
      <div class="link-div">
        <a style="background-image: url(static/image/sisivc/foot/w0.png);">
          <div class="hover-div"></div>
        </a>
        <a style="background-image: url(static/image/sisivc/foot/b0.png);">
          <div class="hover-div" style="background-image: url(static/image/sisivc/foot/wechat.jpg);"></div>
        </a>
        <a style="background-image: url(static/image/sisivc/foot/f0.png);"></a>
        <a style="background-image: url(static/image/sisivc/foot/tw0.png);"></a>
        <a style="background-image: url(static/image/sisivc/foot/ins0.png);"></a>
      </div>
    </div>
    <div class="foot-black">
      <div>
        <span>法律声明&nbsp;FAQs&nbsp;&nbsp;</span>
        <span>31009102000006号&nbsp;&nbsp;</span>
        <span>©️&nbsp;上海艾萨克˙斯特恩国际小提琴比赛沪公网安备 </span>
      </div>
    </div>
  </div>
</template>
<script type="text/ecmascript-6">
export default {
}
</script>
<style type="text/css" scoped>
* {
  font-family: Helvetica, Arial, "Microsoft YaHei", 微软雅黑, SimSun, 宋体, Heiti, 黑体, sans-serif;
}
.foot {
  width: calc(100% - 360px);
  min-width: 1140px;
  margin: 0 auto;
  margin-top: 100px
}
.foot-item {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  justify-content: space-between;
  align-items: start;
  height:200px;
}
.foot .left,.foot .right {
  width: 340px;
}
.foot .center {
  width: 550px;
}
.plate {
  padding: 10px;
  padding-left: 30px;
  padding-top: 15px;
  background-image: url('~static/image/sisivc/foot/email@4x.png');
  background-repeat: no-repeat;
  background-position: 0 10px;
  background-size: 26px auto;
}
.plate h3 {
  margin: 0;
  margin-bottom: 5px;
  font-size: 14px;
  color:#222;
}
.plate p { 
  margin: 0;
  line-height: 30px;
  font-size: 14px;
  color:#a0a0a0;
}
.foot .center ul {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  justify-content: space-between;
  align-items: start;
  padding: 0;
  font-size: 14px;
  padding-top: 5px;
}
.foot .center ul li img {
  width: 22px;
  height: auto;
}
.link-div {
  text-align:center;
  margin-top: 140px;
  margin-bottom: 80px;
  height: 40px;
}
.link-div a {
  width: 40px;
  height: 40px;
  display: inline-block;
  background-image: url('~static/image/sisivc/foot/f.png');
  background-repeat: no-repeat;
  background-size: 40px 40px;
  margin-right:75px;
  position: relative;
}
.link-div a:last-child {
  margin-right:0;
}
li {list-style: none}
.foot-black {
  background-color: #222;
  width: 100%;
  color: #808080;
  height: 60px;
  line-height: 60px;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  justify-content: space-between;
  align-items: start;
  font-size: 12px;
}
.foot-black div{
  margin: 0 auto;
  width:calc(100% - 360px);
  min-width: 1140px;
  text-align: center;
  /* display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  justify-content: space-between;
  align-items: start; */
}
.hover-div {
  position:absolute;
  width:100px;
  height:100px;
  background-image: url('~static/image/sisivc/foot/wechat.jpg');
  background-size:100px 100px;
  background-repeat: no-repeat;
  top:-100px;
  left:calc(50% - 50px);
  display: none;
}
.link-div a:nth-child(1):hover {
  background-image: url('~static/image/sisivc/foot/w.png')!important;
} 
.link-div a:nth-child(2):hover {
  background-image: url('~static/image/sisivc/foot/b.png')!important;
} 
.link-div a:nth-child(3):hover {
  background-image: url('~static/image/sisivc/foot/f.png')!important;
} 
.link-div a:nth-child(4):hover {
  background-image: url('~static/image/sisivc/foot/tw.png')!important;
} 
.link-div a:nth-child(5):hover {
  background-image: url('~static/image/sisivc/foot/ins.png')!important;
} 
.link-div a:nth-child(1):hover .hover-div {
  background-image: url('~static/image/sisivc/foot/wechat.jpg')!important;
} 
.link-div a:nth-child(2):hover  .hover-div{
  background-image: url('~static/image/sisivc/foot/weibo.jpg')!important;
} 
.link-div a:hover .hover-div  {
  display: block;
  -webkit-transition: opacity 3s ease-in-out;
  -moz-transition: opacity 3s ease-in-out;
  -o-transition: opacity 3s ease-in-out;
  transition: opacity 3s ease-in-out;
}
body {margin:0;}
</style>
