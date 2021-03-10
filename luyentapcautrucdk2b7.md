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
  let inputa = prompt('nhập a trong ax^2+bx+c=0 ')
  let inputb = prompt('nhập b trong ax^2+bx+c=0')
  let inputc = prompt('nhập c trong ax^2+bx+c=0')
  let a = parseInt(inputa)
  let b = parseInt(inputb)
  let c = parseInt(inputc)
  let delta = (b*b - 4*a*c)
  let x1
  let x2
  if(delta<0){
    alert("phương trình vô nghiệm")
  }else if(delta=0){
    x1=x2=(-b/(2*a))
    alert("phương trình có nghiệm kép x ="+x1)
  }else{
    x1 = ((-b)+Math.sqrt(delta))/(2*a)
    x2 = ((-b)-Math.sqrt(delta))/(2*a)
    alert("phương trình có 2 nghiệm x1 ="+x1 +"x2 ="+x2)
  }
</script>
</body>
</html>