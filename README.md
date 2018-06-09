
<html>
<head>
    




    

<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover:not(.active) {
    background-color: #111;
}

.active {
    background-color: #4CAF50;
}
 
@font-face {
   font-family: dhivehi;
   src: url(dhivehi.ttf);
}

* {
   font-family: dhivehi;
}

</style>
</head>
<body>
        

<ul>
  <li><a href="">Home</a></li>
  <li><a href="lock">lock</a></li>
  <li><a href="#contact">Contact</a></li>
  <li style="float:right"><a class="active" href="ދިވެހި">ދިވެހި</a></li>
</ul>
<link href="style.css">
	<script src="script.js"></script>
	<script src="script1.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/fastclick/1.0.6/fastclick.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<style>
@font-face {
font-family: "mv waheed";
src: url("https://dl.dropboxusercontent.com/s/z0u7r5sz6ofh6so/MV_Waheed%283%29.otf") format('opentype');
}
@font-face {
font-family: "Mv Faseyha";
src: url("https://dl.dropboxusercontent.com/s/nt4yxgy3xwl40es/Faruma.otf") format('opentype');
}
body {
  font-family:"Mv Faseyha";
  text-align:center;
  background:#f9f9f9;
}
#grid,.box{
  -webkit-user-select:none;
}
#main {
  margin:20px auto;
  max-width:720px;
}
#grid {
  margin:20px auto 40px;
  box-shadow:0 0 20px rgba(0,0,0,0.2);
  width:410px;
  height:410px;
  padding:20px;
  background:#C3E5F1;
  border-radius:10px;
  font-size:20px;
  float:left;
  overflow:hidden;
  cursor:pointer;
}
@media (max-width:740px){
  #grid{
    float:none;
  }
}
@media (max-width:480px){
  #grid{
    margin-bottom:20px;
    padding:5px;
    width:288px;
    height:288px;
    font-size:14px;
    border-radius:5px;
  }
}
.box {
  margin:3px;
  width:45px;
  height:45px;
  line-height:45px;
  text-align:center;
  background:#fff;
  box-shadow:0 0 5px rgba(0,0,0,0.1);
  border-radius:5px;
  float:left;
}
@media (max-width:480px){
  .box{
    width:30px;
    height:30px;
    line-height:30px;
  }
}
.box.highlight{
  background:#111;
  color:#fff;
}
.box.found-red {
  background: #ea2c2c;
  background: -webkit-linear-gradient(#ea2c2c 50%, #d62222 51%);
  background: -moz-linear-gradient(#ea2c2c 50%, #d62222 51%);
  background: -o-linear-gradient(#ea2c2c 50%, #d62222 51%);
  background: linear-gradient(#ea2c2c 50%, #d62222 51%); 
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ea2c2c', endColorstr='#d62222',GradientType=0 );
  color:#fff;
}
.box.found-green {
  background: #a1d54f;
background: -webkit-linear-gradient(#a1d54f 50%, #80c217 51%);
background: -moz-linear-gradient(#a1d54f 50%, #80c217 51%);
background: -o-linear-gradient(#a1d54f 50%, #80c217 51%);
background: linear-gradient(#a1d54f 50%, #80c217 51%); 
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#a1d54f', endColorstr='#80c217',GradientType=0 );
  color:#fff;
}
.box.found-yellow{
  background: #fff94f;
  background: -webkit-linear-gradient(#fff94f 50%, #ffe500 51%);
  background: -moz-linear-gradient(#fff94f 50%, #ffe500 51%);
  background: -o-linear-gradient(#fff94f 50%, #ffe500 51%);
  background: linear-gradient(#fff94f 50%, #ffe500 51%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#fff94f', endColorstr='#ffe500',GradientType=0 );
  color:#fff;
}
.box.found-blue{
  background: #71ceef;
  background: -webkit-linear-gradient(#71ceef 50%, #21b4e2 51%);
  background: -moz-linear-gradient(#71ceef 50%, #21b4e2 51%);
  background: -o-linear-gradient(#71ceef 50%, #21b4e2 51%);
  background: linear-gradient(#71ceef 50%, #21b4e2 51%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#71ceef', endColorstr='#21b4e2',GradientType=0 );
  color:#fff;
}
.box.found-purple {
  background: #c928a9;
  background: -webkit-linear-gradient(#c928a9 49%, #b5177d 49%);
  background: -moz-linear-gradient(#c928a9 49%, #b5177d 49%);
  background: -o-linear-gradient(#c928a9 49%, #b5177d 49%);
  background: linear-gradient(#c928a9 49%, #b5177d 49%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#c928a9', endColorstr='#b5177d',GradientType=0 );
  color:#fff;
}
#listContainer {
  margin:20px 0 0 20px;
  padding:20px;
  float:left;
  height:410px;
  width:200px;
  box-shadow:0 0 20px rgba(0,0,0,0.1);
  background:#C3E5F1;
  border-radius:10px;
}
@media (max-width:740px){
  #listContainer{
    margin:auto;
    float:none;
    width:250px;
    height:auto;
    padding-top:5px;
  }
}
#list{
  margin:auto;
  padding-left:20px;
  font-size:20px;
  text-align:right;
  list-style:none;
}
#list li.found{
  color:gray;
  text-decoration:line-through;
}
#restart {
  margin:20px auto 0;
  line-height:40px;
  background:rgba(0,0,0,0.1);
  border-radius:5px;
  cursor:pointer;
  display:none;
}
</style>
<body>
<div id="main">
  <div id="x8"></div>
  <div id="grid">
    <div class="box" data-word="Apple">ރީ</div><div class="box" data-word="Apple">ބެ</div><div class="box" data-word="Apple">ރޯ</div><div class="box" data-word="Apple">ޓް</div><div class="box" data-word="Apple">ސް</div><div class="box">މި</div><div class="box">ވަ</div><div class="box" data-word="Pizza">އި</div><div class="box">ފަ</div><div class="box">ސް</div><div class="box">ވި</div><div class="box">ބަ</div><div class="box">ޒޭ</div><div class="box">ޕެ</div><div class="box">ރި</div><div class="box" data-word="Pizza">ސް</div><div class="box">ޖޮ</div><div class="box" data-word="Grape">ޖަ</div><div class="box">ގޭ</div><div class="box">މަ</div><div class="box" data-word="Cake">ޖު</div><div class="box">ރޭ</div><div class="box">ޔާ</div><div class="box" data-word="Pizza">ބަ</div><div class="box">ތީ</div><div class="box">ބު</div><div class="box" data-word="Grape">ނ</div><div class="box" data-word="Cake">ން</div><div class="box">ރި</div><div class="box">ސާ</div><div class="box">ން</div><div class="box" data-word="Pizza">ގު</div><div class="box">ވާ</div><div class="box">އި</div><div class="box" data-word="Cake">ރެ</div><div class="box" data-word="Grape">ބު</div><div class="box">ޑި</div><div class="box">ހި</div><div class="box">ދު</div><div class="box" data-word="Pizza">ލު</div><div class="box">ކި</div><div class="box" data-word="Cake">އޮ</div><div class="box">ގެ</div><div class="box">މާ</div><div class="box" data-word="Grape">ރޯ</div><div class="box">ލޮ</div><div class="box">ހާ</div><div class="box">ން</div><div class="box">ރި</div><div class="box">ސަ</div><div class="box">ބެ</div><div class="box">ޔު</div><div class="box">ޒާ</div><div class="box" data-word="Grape">ލު</div><div class="box">ޗި</div><div class="box">ލީ</div><div class="box" data-word="Sandwic">ވާ</div><div class="box" data-word="Sandwic">މޭ</div><div class="box" data-word="Sandwic">ތު</div><div class="box" data-word="Sandwic">އް</div><div class="box" data-word="Sandwic">ހު</div><div class="box" data-word="Sandwic">ޅު</div><div class="box" data-word="Sandwic">ކަ</div><div class="box">އި</div>
  </div>
  <div id="listContainer">
    <h2>ހޯދަންވީ ބަސްތައް</h2>
    <ul id="list">
      <li>ސްޓްރޯބެރީ</li>
      <li>ޖަނބުރޯލު</li>
      <li>އިސްބަގުލު</li>
      <li>އޮރެންޖު</li>
      <li>ކަޅުހުއްތުމޭވާ</li>
    </ul>
    <div id="restart">
      އަލުން ގޭމް ފައްޓާ
    </div>
  </div>
</div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/fastclick/1.0.6/fastclick.min.js"></script>


</body>
</html>
