<template>
  <div id="hello">
    <header class="bgimg w3-container" style="padding:170px 140px">
      <p class="w3-xlarge" style="color:#e600e6;font-weight:bold">重庆敏捷化工产品有限公司</p>
      <h4 class="vintage w3-margin w3-center w3-jumbo">金属表面 处理专家</h4>
      <p class="w3-xlarge w3-right" style="font-style:italic;font-weight:bold">--------{{ msg }}</p>
    </header>
    <div class="tab">
      <button class="tablinks" onmouseover="openCity(event, 'London')"><i class='fa fa-phone' style='font-size:48px;color:black'></i>热线电话</button>
      <button class="tablinks" onmouseover="openCity(event, 'Paris')"><img src="../../src/assets/ma.jpg" style="width:36px;height:36px;">微信扫一扫</button>
      <button class="tablinks" onmouseover="openCity(event, 'Tokyo')"><i class='fa fa-qq' style='font-size:36px;color:black'></i>QQ在线</button>
    </div>
    <div id="London" class="tabcontent">
  <h3>London</h3>
  <p>London is the capital city of England.</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Paris</h3>
  <p>Paris is the capital of France.</p>
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>

<div class="clearfix"></div>

  <div class="w3-row-padding w3-padding-64 w3-container">
    <div class="w3-content">
      <div class="w3-twothird">
        <h1>主营业务</h1>
        <p class="w3-padding-32">公司主要生产<span style="color:purple;font-size:23px;">商用清洗剂、商用清洗消毒剂、工业清洗剂类</span>等一系列清洁产品。清洗是采用溶剂（包括水、化学溶剂等等）清除物体表面污垢的方法。它是机械外力的辅助作用（如机械搅拌、超声波高频振荡）或是借助清洗剂对表面污染物或覆盖层进行化学转化、溶解、剥离以达到脱脂、除锈和去污的效果。
          清洗分为化学清洗，物理清洗，微生物清洗、激光清洗。商用清洁主要包括物业保洁、酒店清洁、市政保洁、医院保洁、商超保洁、学校保洁、机关单位保洁、建筑物外墙清洗、空调清洗、石材护理、日常生活环境中的其他清洗及其应用等。工业清洗为工业生产设备、交通工具、航天、航海设备等提供的清洗服务。
          要经济快速实现清洗目的需要选择正确的清洗剂...<a href="#">详细内容</a>
        </p>
        <h5>重庆友轩力环保科技有限公司生产的系列工业与家用清洗护理产品就是客户的最优选择。</h5>
      </div>
      <div class="w3-third w3-center">
        <i class="fa fa-anchor w3-padding-64 w3-text-blue"></i>
      </div>
    </div>
  </div>
  <div class="w3-row-padding w3-light-grey w3-padding-64 w3-container">
    <div class="w3-content">
      <div class="w3-third w3-center">
        <i class="fa fa-bullhorn w3-padding-64 w3-text-blue w3-margin-right"></i>
      </div>
      <div class="w3-twothird">
        <h1>热销商品</h1>
        <h5 class="w3-padding-32">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</h5>
        <ol class="w3-text-grey">
          <li>bla</li>
          <li>blabla</li>
          <li>bla</li>
          <li>shenme</li>
          <li>suibian</li>
          <li>bcsa</li>
        </ol>
        <a href="#">详细内容</a>
      </div>
    </div>
  </div>
  <!-- The Band Section -->
  <div class="w3-container w3-content w3-center w3-padding-64" style="max-width:1200px" id="band">
    <h2 class="w3-wide">我们的优势</h2>
    <p class="w3-opacity"><i>3大优势</i></p>
    <p class="w3-justify">10年专注生产研发各种清洁产品,拥有丰富的项目经验。拥有学院研发技术人员30余人，公司每年研发经费投入占比达4%, 拥有万平厂房，具备高柔性的制造加工能力， 弹性生产能力。专业的技术团队，满足定制需求，快速响应客户，提供专业的环保设备整体解决方案。
      公司提供方案咨询、设备选型、图纸设计、 设备制造、贴牌服务及代加工生产，360度贴心到家。</p>
    <div class="w3-row w3-padding-16">
      <div class="w3-third">
        <p>研发优势</p>
        <img src="../../src/assets/walter.jpg" class="w3-round w3-margin-bottom" alt="Random Name" style="width:80%">
      </div>
      <div class="w3-third">
        <p>制造优势</p>
        <img src="../../src/assets/vee.jpg" class="w3-round w3-margin-bottom" alt="Random Name" style="width:80%">
      </div>
      <div class="w3-third">
        <p>服务优势</p>
        <img src="../../src/assets/communications.jpg" class="w3-round" alt="Random Name" style="width:80%">
      </div>
    </div>
  </div>
  <div class="w3-row-padding w3-padding-64 w3-container">
    <div class="w3-content">
      <div class="w3-twothird">
        <h1>联系我们</h1>
        <ul class="w3-padding-32">
          <li>服务热线：023-88665473</li>
          <li>服务时间：24小时/天</li>
          <li>联系人：卢经理</li>
          <li>传真：023-88665473</li>
          <li>邮箱：2401660049@qq.com</li>
          <li>传真：023-88665473</li>
          <li>公司地址：重庆市大渡口区御景天都5幢7-3号 </li>
        </ul>
        <h5>欢迎垂询、商务合作</h5>
      </div>
      <div class="w3-third w3-center">
        <i class="fa fa-coffee w3-padding-64 w3-text-blue"></i>
      </div>
    </div>
  </div>
  <footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge">
      <i class='fa fa-qq' style='font-size:36px;padding:40px;'></i>
      <i class='fa fa-weixin' style='font-size:36px;padding:40px;'></i>
      <i class='fa fa-weibo' style='font-size:36px;padding:40px;'></i>
      <p style="font-size:15px;">版权所有：<a href="https://www.w3schools.com/w3css/default.asp" target="_blank">Copyright © 2002-2020 重庆敏捷化工产品有限责任公司版权所有</a></p>
      <p style="font-size:15px;">备案号：564651132</p>
      <p>地址：重庆市大渡口区御景天都5幢7-3号</p>
      <p>电话：023-88665473</p>
      <p style="font-size:15px;">技术支持：迪猪网络</p>
  </footer>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods:{
    openCity: function(evt, cityName) {
      var i, tabcontent, tablinks;
      tabcontent = document.getElementsByClassName("tabcontent");
      for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
      }
      tablinks = document.getElementsByClassName("tablinks");
      for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
      }
      document.getElementById(cityName).style.display = "block";
      evt.currentTarget.className += " active";
    }
  }
}
</script>

<style scoped>
.bgimg {
  background-image: url('../../src/assets/sea.jpg');
  min-height: 100%;
  background-position: center;
  background-size: cover;
}

h5{
  font-style: italic;
  color:orange;
}
.fa-anchor,.fa-coffee, .fa-car, .fa-bullhorn{font-size:200px}
.vintage{
  font-style: italic;
  background: #EEE url(data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAQAAAAECAIAAAAmkwkpAAAAHklEQVQImWNkYGBgYGD4//8/A5wF5SBYyAr+//8PAPOCFO0Q2zq7AAAAAElFTkSuQmCC) repeat;
  text-shadow: 5px -5px yellow, 4px -4px white;
  font-weight: bold;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
}
.tab {
  position: -webkit-sticky;
  position: sticky;
  float: right;
  top: 100px;
  padding: 5px 5px 5px 5px;
}
.tab button{
  display: block;
  background-color: inherit;
  color:green;
  padding: 22px 16px;
  width: 100%;
  border: none;
  outline: none;
  text-align: left;
  cursor: pointer;
}
.tab button:hover {
  background-color: #ddd;
}

.tab button.active {
  background-color: #ccc;
}

.tabcontent {
  float: left;
  padding: 0px 12px;
  border: 1px solid #ccc;
  width: 70%;
  border-left: none;
  height: 300px;
  display: none;
}
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
</style>
