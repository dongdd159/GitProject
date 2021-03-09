<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
</head>
<body>
<label for="month">Nhập tháng</label>
<input type="number" name="month" id="month">
<input type="button" value="Tính số ngày" onclick="countdate()"><br/>
<p id="dates"></p>
<script>
  var inputmonth
  function countdate() {
    inputmonth = document.getElementById("month").value
    var month = parseInt(inputmonth)
    switch (month){
      case 1:
      case 3:
      case 5:
      case 7:
      case 8:
      case 10:
      case 12:
        document.getElementById("dates").innerHTML="Tháng" + month + "có 31 ngày"
        break;
      case 2:
        document.getElementById("dates").innerHTML="Tháng" + month + "có 28 hoặc 29 ngày"
        break;
      default:
        document.getElementById("dates").innerHTML="Tháng" + month + "có 30 ngày"
    }
  }
</script>
</body>
</html>
