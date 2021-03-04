<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title></title>
</head>
<body>
<form method="get">
    <table>
        <tr>
            <th bgcolor="#ff7f50" colspan="3" style="color: aliceblue"> SỞ THÍCH CỦA BẠN </th>
        </tr>
        <tr>
            <td>Họ và tên</td>
            <td><input type="text" name="yourname"/></td>
            <td></td>
        </tr>
        <tr>
            <td>Email</td>
            <td><input type="text" name="email" size="12%"/></td>
            <td></td>
        </tr>
        <tr>
            <td>Sở thích</td>
            <td><label style="color: coral"><input type="checkbox" name="hobby" value="sport"/>Thể thao</label>
                <label style="color: coral"><input type="checkbox" name="hobby" value="music"/>Âm nhạc</label>
            </td>
            <td><label style="color: coral"><input type="checkbox" name="hobby" value="reading"/>Đọc sách</label>
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <label style="color: coral"><input type="checkbox" name="hobby" value="internet"/>Lướt web</label>
                <label style="color: coral"><input type="checkbox" name="hobby" value="gaming"/>Chơi game</label>
            </td>
            <td>
                <label style="color: coral"><input type="checkbox" name="hobby" value="cinematic"/>Điện ảnh</label>
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <label style="color: coral"><input type="checkbox" name="hobby" value="travel"/>Du lịch</label>
            </td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>
                <input type="submit" value="Submit form"/>
                <input type="reset" value="Reset form"/>
            </td>
            <td></td>
        </tr>
    </table>
    </form>
</body>
</html>