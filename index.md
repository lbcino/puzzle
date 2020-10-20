<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Puzzle</title>
  <meta name="viewport" content="user-scalable=no, width=device-width, initial-scale=1, maximum-scale=1.0,  minimum-scale=1, shrink-to-fit=yes">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <link rel="stylesheet" href="puzzle.css">

</head>
<body>

<div id="container">	
	<a href="#" ><img class="start-image start" src="start2.png"></a>
	<div class="box">	
		<div class="me full"></div>
	</div>
	<div class="pre_img">	
		<li data-bid="0"><img src="polarbear.png"></li>
		<!--<li data-bid="1"><img src="https://preview.ibb.co/kWOEt6/minion.png"></li>
		<li data-bid="2"><img src="https://preview.ibb.co/e0Rv0m/ab.jpg"></li>	
				<input type="file" name="image" id="file1" style="display: none"> -->
	</div>
	<div align="center"><a href="#" class="button reset" align="center">Reset</a></div>
</div>

<div class="score-container" >
	<div class="score">
		<p id="scr_head"><br>You Did It! </p>
		<p id="scr_time"> Time : <span id="min">00</span> Min <span id="sec">00</span> Sec</p>
		<p id="scr_moves"> Moves : <span id="moves"></span></p>
        <div class="ok-container"> <img class="ok-button" src="ok.png"> </div>
	</div>
</div>

  <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js'></script><script  src="puzzle.js"></script>

</body>
</html>

  
