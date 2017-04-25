<html>
<head>

  </head>
  
<script>
  $(document).ready(function() {

    $("#left-well").css("background-color", "gray");
    $("#right-well").css("background-color", "gray");
    $("#right-well").children().css("color", "blue");
    $("#left-well").children().css("color", "blue");
    $(".target:even").addClass("animated shake");
   $("#target6").addClass("animated fadeOut");
    $("#target5").addClass("animated fadeOut");
    $("#target4").addClass("animated fadeOut");
    $("#right-well").addClass("animated fadeOut");
  $("h2").addClass("animated hinge ");
      $("p").addClass("animated shake");  
      $("img").addClass("animated shake");  
  });  
  </script>
<body BACKGROUND="http://kabegami.org/wp-content/uploads/2013/04/YjHrXl.jpg"> 
<h1 style="color:black">天婦羅介紹by 404262212資工二乙 李京倫</h1>
<h2 style="color:black">我最近最想吃的料理</h2>
<img class="smaller-image" src="http://p03.sfbest.com/2012/07/%E5%A4%A9%E5%A6%87%E7%BD%97%20%E9%85%8D%E5%9B%BE%E4%BA%8C.jpg" alt="Author standing on a beach with two thumbs up. ">
<p>最早源自拉丁语系葡萄牙语的Tempura发音，是由16世纪时的葡萄牙传教士传入日本，当初是葡萄牙人在大斋期（Lent，天主教节日，指复活节六个半星期以前）期间因禁吃兽肉，只能食用海鲜，而以吃鱼代替肉而烹煮的一种食物。其中，拉丁文的“ad tempora quadragesima”就是“守大斋期”的意思。后来在日本逐渐流行起来。传统的日式天妇罗是用海产或蔬菜裹上淀粉浆（面粉之类）油炸。</p>
<h2 style="color:black">天婦羅的種類</h2>
<ul>
  <li>以魚,貝,蝦為原料用麵衣包裹</li>
  <li>以魚漿為原料,又稱甜不辣</li>
</ul>


 <div class="container-fluid">
 
  <div class="row">
    <div class="col-xs-7">
      <h4>調料</h4>
      <div class="well" id="left-well">
        <button class="btn btn-default target" id="target1">醬油</button>
        <button class="btn btn-default target" id="target2">芥末</button>
        <button class="btn btn-default target" id="target3">甜辣醬</button>
      </div>
    </div>
    <div class="col-xs-7">
     <h4></h4>
      <div class="well" id="right-well">
        <button class="btn btn-default target" id="target4">美乃滋</button>
        <button class="btn btn-default target" id="target5">塔塔醬</button>
        <button class="btn btn-default target" id="target6">海苔粉</button>
      </div>
    </div>
  </div>
</div>

</body>

</html>
