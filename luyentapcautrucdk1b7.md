<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
  <style>
  </style>
</head>
<body>
<script>
  let sophutgoi = parseInt(prompt('nhập số phút'))
  let tiencuoc
  if(sophutgoi<=50){
    tiencuoc=sophutgoi*600+25000
  }else if(sophutgoi<=200){
    tiencuoc=50*600+(sophutgoi-50)*400+25000
  }else {
    tiencuoc = 50 * 600 + 150 * 400 + (sophutgoi - 200) * 200 + 25000
  }
  alert("số tiền cước:"+tiencuoc)
</script>
</body>
</html>
