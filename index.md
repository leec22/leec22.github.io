
  
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

  });  
  </script>

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
    
     <h4>#right-well</h4>
      <div class="well" id="right-well">
        <button class="btn btn-default target" id="target4">#target4</button>
        <button class="btn btn-default target" id="target5">#target5</button>
        <button class="btn btn-default target" id="target6">#target6</button>
      </div>
    </div>
  </div>
</div>




