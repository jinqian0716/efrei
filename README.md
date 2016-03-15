# efrei
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=0">
    <title></title>
    <link rel="stylesheet" href="../style/weui.css"/>
    <link rel="stylesheet" href="./example.css"/>
	<script type="text/javascript" src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.8.0.js"></script>
	<script type="text/javascript">
		$(document).ready(function(){
		$("#a1").hide();
		$("#b1").click(function(){
		$("#a1").toggle();
		});
		});
		$(document).ready(function(){
		$("#a2").hide();
		$("#b2").click(function(){
		$("#a2").toggle();
		});
		});
		$(document).ready(function(){
		$("#a3").hide();
		$("#b3").click(function(){
		$("#a3").toggle();
		});
		});
		$(document).ready(function(){
		$("#a4").hide();
		$("#b4").click(function(){
		$("#a4").toggle();
		});
		});
		$(document).ready(function(){
		$("#a5").hide();
		$("#b5").click(function(){
		$("#a5").toggle();
		});
		});
 
	</script>
</head>
<body ontouchstart>

<div class="page">
    <div class="hd">
        <h1 class="page_title">采矿摄像</h1>
    </div>
    <div class="bd">
        
        

        <div class="weui_cells_title">摄像列表
        <div class="weui_cells weui_cells_access">
            
				<button id="b1">采矿位置1</button>
				<div id="a1">
					<iframe height=154 width=305 src="http://demo.anyan.com/video/view?device_id=Ub0000000542866896QB" > 
					</iframe>
				</div>
        </div>

        <div class="weui_cells weui_cells_access">
            
				<button id="b2">采矿位置2</button>
				<div id="a2">
					<iframe height=154 width=305 src="http://demo.anyan.com/video/view?device_id=Ub0000000536914147Ye">
					</iframe>
				</div>
        </div>
	
        <div class="weui_cells weui_cells_access">
            
				<button id="b3">采矿位置3</button>
				<div id="a3">
					<iframe height=154 width=305 src="http://demo.anyan.com/video/view?device_id=Ub000000FCFD01AD58eF">
					</iframe>
				</div>
        </div>

        <div class="weui_cells weui_cells_access">
            
				<button id="b4">采矿位置4</button>
				<div id="a4">
					<iframe height=154 width=305 src="http://demo.anyan.com/video/view?device_id=Ub0000000542866896QB">
					</iframe>
				</div>
        </div>

        <div class="weui_cells weui_cells_access">
            
				<button id="b5">采矿位置5</button>
				<div id="a5">
					<iframe height=154 width=305 src="http://demo.anyan.com/video/view?device_id=Ub0000000536914147Ye">
					</iframe>
				</div>
		</div>
        </div>
    </div>
     

    </div>
</div>
    
    <script src="./zepto.min.js"></script>
    <script src="./example.js"></script>
</body>
</html>
