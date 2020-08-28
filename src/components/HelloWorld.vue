<template>
  <div id="hello">
    <div class="tab">
      <button class="tablinks"  v-on:mouseover="openCity(event, 'London')"><i class='fa fa-phone' style='font-size:48px;color:black'></i>热线电话</button>
      <button class="tablinks" v-on:mouseover="openCity(event, 'Paris')"><img src="../../src/assets/ma.jpg" style="width:36px;height:36px;">扫一扫</button>
      <button class="tablinks" v-on:mouseover="openCity(event, 'Tokyo')"><i class='fa fa-qq' style='font-size:36px;color:black'></i>QQ在线</button>
    </div>
    <header class="bgimg w3-container" style="padding:128px 30px">
      <p class="w3-xlarge">重庆敏捷化工产品有限公司</p>
      <h4 class="vintage w3-margin w3-center w3-jumbo">金属表面 处理专家</h4>
      <p class="w3-xlarge w3-right" style="font-style:italic;font-weight:bold">--------{{ msg }}</p>
    </header>
  <div class="w3-row-padding w3-padding-32 w3-container">
    <div class="w3-content">
      <div class="w3-twothird">
        <h1>主营业务</h1>
        <p class="w3-padding-32">公司主要生产<span style="color:purple;font-size:23px;">商用清洗剂、商用清洗消毒剂、工业清洗剂类</span>等一系列清洁产品。清洗是采用溶剂（包括水、化学溶剂等等）清除物体表面污垢的方法。它是机械外力的辅助作用（如机械搅拌、超声波高频振荡）或是借助清洗剂对表面污染物或覆盖层进行化学转化、溶解、剥离以达到脱脂、除锈和去污的效果。
          清洗分为化学清洗，物理清洗，微生物清洗、激光清洗。商用清洁主要包括物业保洁、酒店清洁、市政保洁、医院保洁、商超保洁、学校保洁、机关单位保洁、建筑物外墙清洗、空调清洗、石材护理、日常生活环境中的其他清洗及其应用等。工业清洗为工业生产设备、交通工具、航天、航海设备等提供的清洗服务。
          要经济快速实现清洗目的需要选择正确的清洗剂,重庆敏捷化工产品有限公司推出的系列工业与家用清洗护理产品就是客户的最优选择。...<a href="#" style="color:red;">详细内容</a>
        </p>
      </div>
      <div class="w3-third w3-center">
        <img src="../../src/assets/unnamed.jpg" class="w3-padding-64" alt="Random Name" style="width:100%">
      </div>
  </div>
  </div>
  <div class="w3-light-grey" id="tour">
    <div class="w3-container w3-content w3-padding-32" style="max-width:800px">
      <h2 class="w3-wide w3-center">热销产品</h2>
      <p class="w3-opacity w3-center"><i>欢迎在线订购!</i></p><br>

      <ul class="w3-ul w3-border w3-white w3-text-grey">
        <li class="w3-padding">无铬钝化剂<span class="w3-tag w3-red w3-margin-left">欲购从速</span><span class="w3-badge w3-right w3-margin-right">3</span></li>
        <li class="w3-padding">高分子处理剂<span class="w3-tag w3-red w3-margin-left">欲购从速</span><span class="w3-badge w3-right w3-margin-right">3</span></li>
        <li class="w3-padding">酸雾抑制剂<span class="w3-badge w3-right w3-margin-right">10</span></li>
      </ul>

      <div class="w3-row-padding w3-padding-16" style="margin:0 -16px">
        <div class="w3-third w3-margin-bottom">
          <img src="../../src/assets/wuluo.jpeg" alt="New York" style="width:100%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>无铬钝化剂</b></p>
            <p class="w3-opacity">Fri 27 Nov 2016</p>
            <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">详细信息</button>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
          <img src="../../src/assets/高分子.jpeg" alt="Paris" style="width:100%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>高分子处理剂</b></p>
            <p class="w3-opacity">Sat 28 Nov 2016</p>
            <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.
              Praesent tincidunt sed tellus ut rutrum sed vitae justo.
              Praesent tincidunt sed tellus ut rutrum sed vitae justo.
            </p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">详细信息</button>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
          <img src="../../src/assets/酸雾.jpeg" alt="San Francisco" style="width:100%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>酸雾抑制剂</b></p>
            <p class="w3-opacity">Sun 29 Nov 2016</p>
            <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">详细信息</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="w3-container w3-content w3-center w3-padding-32" style="max-width:1200px" id="band">
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
  <div class="w3-row-padding w3-padding-32 w3-container w3-light-grey">
    <div class="w3-content">
      <div class="w3-two">
        <h2 class="w3-wide w3-center">联系我们</h2>
        <p class="w3-opacity w3-center"><i>给我们留言</i></p>
        <div class="w3-row w3-padding-16">
          <div class="w3-col m6 w3-large w3-margin-bottom">
            <i class="fa fa-map-marker" style="width:30px"></i>公司地址：重庆市大渡口区御景天都5幢7-3号 <br>
            <i class="fa fa-phone" style="width:30px"></i>服务热线: 023-88665473<br>
            <i class="fa fa-envelope" style="width:30px"> </i>邮箱：2401660049@qq.com<br>
            <i class="fa fa-fax" style="width:30px"> </i>传真：023-88665473<br>
            <i class="fa fa-hand-o-right" style="width:30px"></i>联系人：卢经理<br>
          </div>
          <div class="w3-col m6 w3-large w3-margin-bottom">
            <form action="/action_page.php" target="_blank">
              <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
                <div class="w3-half">
                  <input class="w3-input w3-border" type="text" placeholder="姓名" required name="Name">
                </div>
                <div class="w3-half">
                  <input class="w3-input w3-border" type="text" placeholder="电话" required name="Phone">
                </div>
              </div>
              <input class="w3-input w3-border" type="text" placeholder="留言" required name="Message">
              <button class="w3-button w3-black w3-section w3-right" type="submit">发送</button>
            </form>
        </div>
  </div>
</div>
</div>
</div>
  <footer class="w3-container w3-padding-64 w3-blue w3-center w3-xlarge">
      <i class='fa fa-qq' style='font-size:36px;padding:40px;'></i>
      <i class='fa fa-weixin' style='font-size:36px;padding:40px;'></i>
      <i class='fa fa-weibo' style='font-size:36px;padding:40px;'></i>
      <div style="font-size:15px;">
        <p>版权所有：<a href="https://www.w3schools.com/w3css/default.asp" target="_blank">Copyright © 2002-2020 重庆敏捷化工产品有限责任公司版权所有</a></p>
        <p>备案号：564651132</p>
        <p>地址：重庆市大渡口区御景天都5幢7-3号</p>
        <p>电话：023-88665473</p>
        <p>技术支持：迪猪网络</p>
      </div>
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
  top: 45px;
}
.tab button{
  display: block;
  background-color: ivory;
  margin-bottom: 5px;
  color:slateblue;
  padding: 5px 5px;
  width: 100%;
  border:none;
  outline: none;
  text-align: right;
  cursor: pointer;
  font-size: 15px;
}

.tab button:hover {
  background-color: rgb(40, 212, 161);
}

.tab button.active {
  background-color: #ccc;
}

.tabcontent {
  position: -webkit-sticky;
  position: sticky;
  float: right;
  top: 100px;
  float: right;
  padding: 0px 12px;
  border: 1px solid #ccc;
  width: 120px;
  height: 120px;
  display: none;
}
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
</style>
