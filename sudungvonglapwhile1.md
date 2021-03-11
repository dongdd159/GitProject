<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
  <style>
  </style>
</head>
<body>
<h2>JavaScript Loops</h2>
<p id="demo"></p>
<script>
  let num
  let total = 0;
  while( num != -1 ) {
    num = parseInt(prompt("Enter a number: "));
    total += num;
  }
  alert(total)
</script>
</body>
</html>
