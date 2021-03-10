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
  let inputsodien = prompt('nhập kWh')
  let sodien = parseFloat(inputsodien)
  let sotien
  if(sodien>0&&sodien<=50){
    sotien = sodien*1678
  }else if(sodien<=100){
    sotien= 50*1678+(sodien-50)*1734
  }else if(sodien<=200){
    sotien= 50*1678+50*1734+(sodien-100)*2014
  }else if(sodien<=300){
    sotien= 50*1678+50*1734+50*2014+(sodien-150)*2536
  }else if(sodien<=400){
    sotien= 50*1678+50*1734+50*2014+50*2536+(sodien-200)*2834
  }else{
    sotien= 50*1678+50*1734+50*2014+50*2536+50*2834+(sodien-250)*2927
  }
  alert("tổng tiền điện:"+sotien)
</script>
</body>
</html>
