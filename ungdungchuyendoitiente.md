<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<form>
<p>Amount</p>
<input type="number" id="amountid">
<label for="fromcurrency">From currency</label>
<select id="fromcurrency">
    <option value="fromVND">VNĐ</option>
    <option value="fromUSD">USD</option>
</select>
<label for="tocurrency">To currency</label>
<select id="tocurrency">
    <option value="toVND">VNĐ</option>
    <option value="toUSD">USD</option>
</select>
<input type="button" value="Convert" onclick="convert()">
</form>
<p style="color: blue" id="after"></p>
<script>
    function convert() {
        var inputamount = document.getElementById("amountid").value
        var from = document.getElementById("fromcurrency").value
        var to = document.getElementById("tocurrency").value
        if(to=="toUSD"){
            var unit = "đô la"
        }else{
            unit = "đồng"
        }
        if(from=="fromVND"&&to=="toUSD") {
            var aftercon = inputamount * 0.000043
        }else if(from=="fromUSD"&&to=="toVND") {
            aftercon = inputamount * 23071
        }else{
            aftercon = inputamount
        }
        document.getElementById("after").innerHTML = aftercon + unit;
    }
</script>
</body>
</html>