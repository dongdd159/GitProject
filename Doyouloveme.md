<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
  <style>
    .form{
      margin: 0 auto;
      display: flex;
      justify-content: center;
      align-items: center;
    }
  </style>
</head>
<body>
<div class="form" >
<div align="center">
  <h1>Do you love me</h1>
</div>
<div align="center"><input type="button" value="Yes" onclick="yes()"><input type="button" value="No" id="No" onmouseover="no()" position="relative" ></div>
</div>
  <script>
  let maxh = window.innerHeight
  let maxw =  window.innerWidth
  window.onload = init();
  function yes(){
  alert("<3")
}
function init() {
  var nope = document.getElementById("No");
  nope.style.position = 'relative';
  nope.style.left = '0px';
}
  function getRndInteger(min, max) {
    return Math.floor(Math.random() * (max - min + 1) ) + min;
  }
function no(){
  var nope = document.getElementById("No")
  nope.style.left = Math.floor((Math.random() * maxw) - maxw) + 'px'
  nope.style.top = Math.floor((Math.random() * maxh) - maxh) + 'px'
}

</script>
</body>
</html>
