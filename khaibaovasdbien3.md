<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>

<script>
    function check() {
        var a = prompt("input", "a")
        var b = prompt("input", "b")
        if (a % b == 0) {
            return "chia het"
        } else {
            return "ko chia het"
        }
    }
    alert(check())
</script>
</body>
</html>