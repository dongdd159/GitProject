<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<form>
<input type="number" id="a"><input type="number" id="b"><br/>
    <input type="button" value="Addition(+)" id="add" onclick="addition()">
    <input type="button" value="Subtraction(-)" id="sub" onclick="subtraction()">
    <input type="button" value="Multiplication(x)" id="mul" onclick="multiplication()">
    <input type="button" value="Division(:)" id="div" onclick="division()">
</form>
<p id="result"></p>
<script>
    var a,b
    function takevalue(){
        var inputa = document.getElementById("a").value
        a = parseInt(inputa)
        var inputb = document.getElementById("b").value
        b = parseInt(inputb)
    }
    function addition(){
        takevalue()
        var total = a+b
        document.getElementById("result").innerHTML = total
    }
    function subtraction() {
        takevalue()
        var sub = a-b
        document.getElementById("result").innerHTML = sub
    }
    function multiplication() {
        takevalue()
        var mul = a*b
        document.getElementById("result").innerHTML = mul
    }
    function division() {
        takevalue()
        var div = a/b
        document.getElementById("result").innerHTML = div
    }
</script>
</body>
</html>