<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
</head>
<body>
<label for="weight">Cân nặng</label>
<input type="number" name="weight" id="weight">
<label for="weight">Chiều cao</label>
<input type="number" name="height" id="height">
<input type="button" value="Category" onclick="category()">


<script>
  var inputweight
  var inputheight
  function category() {
    inputweight = document.getElementById("weight").value
    inputheight = document.getElementById("height").value
    var weight = parseFloat(inputweight)
    var height = parseFloat(inputheight)
    var bmi = weight / (height * height)
    if (bmi < 18)
      document.write("Underweight");
    else if (bmi < 25)
      document.write("Normal");
    else if (bmi < 30)
      document.write("Overweight");
    else
      document.write("Obese");
  }
</script>
</body>
</html>