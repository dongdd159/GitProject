<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
</head>
<body>
<script>
  let sout = "<table border='1'>"
  let kq=0
  for(let i =1;i<=9;i++){
    sout=sout +"<tr>"
    for (let j =2;j<=9;j++){
      kq=i*j
      sout=sout+"<td>"+j+"x"+i+"="+kq+"</td>"
    }
    sout=sout +"</tr>"
  }
  sout=sout+"</table>"
  document.write(sout)
</script>
</body>
</html>