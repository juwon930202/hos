# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .blinking{ -webkit-animation:blink 1.5s ease-in-out infinite alternate; -moz-animation:blink 1.5s ease-in-out infinite alternate; animation:blink 1.5s ease-in-out infinite alternate; } @-webkit-keyframes blink{ 0% {opacity:0;} 100% {opacity:1;} } @-moz-keyframes blink{ 0% {opacity:0;} 100% {opacity:1;} } @keyframes blink{ 0% {opacity:0;} 100% {opacity:1;} }
    </style>
    <style>
        input[type=checkbox]:checked+div
        {
            height:300px;
        }
        div{
            overflow:hidden;
            width:650px;
            height: 0px;

            transition-duration: 2s;
            -webkit-transition-duration:2s ;
            -moz-transition-duration: 2s;
        }
        #check {display:none}
    </style>
    <style>
        label{color:white}
        #header>h1{color:rgb(255, 255, 255)}
        p{color:white}
        span{color:white}
    </style>
    <style>
        body{
            background-image: url(https://img.hankyung.com/photo/202102/57566_110377_1543.jpg);
        }
    </style>
    <style>
    .video{
	width: 100%; 
    height: 550px; 
  	}
  
video[poster]{ 
    height:100%;
    width:100%;
    }
    </style>
</head>
<body>
</div>
<div class="video">
    <video width="100%" poster="https://i.ytimg.com/vi/NzG-4gDDazg/maxresdefault.jpg" autoplay loop controls>
      <source src="hos1.mp4" type="video/mp4">
    </video>
</div>
    <br>
    <br>
    <label for="check">궁금하지않겠지만</label>
    <input id="check" type="checkbox">
    <div id=header>
        <h1>김주원</h1>
        <p>나이 : 29세</p>
        <p>취미 : 게임</p>
        <p>적을게 : 없다</p>
        <p>마스크 : 쓰기싫다</p>
        <p>디아블로 : 해본적없음</p>
        <span class="image blinking"> 시공 : 좋아 </span>
</body>
</html>
