# katiejauch.github.io
<html lang="en">
<head>
<!-- Lab 12A Katie Jauch, H01, 11/02/2023 -->
<meta charset="utf-8">
<title>Lab 12A KJ</title>

<style>
    body{background-color: white;}
    h1{color:darkgreen;}
    h2{color:red;}
    img{position: absolute; top: 100px; left: 50%;}
    div{position: absolute; top: 250px; left: 50%; font-size: 60px;}
</style>

<script>
    
  function unwrap(){
    document.getElementById("gift").src = "lab12images/coal.jpeg";
    document.getElementById("bad").innerHTML = "Better luck next year!";
  }

  
</script>

</head>
<body>

<h1>Merry Christmas to my Favorite Brother!!</h1>

<h2>Unwrap your present!!</h2>

<img id="gift" src="lab12images/present.png" alt="unwrap the present" onmouseover="unwrap()">

<div id="bad">

</div>

</body>
</html>
