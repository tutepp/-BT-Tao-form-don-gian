# -BT-Tao-form-don-gian
<html>
<head>
    <meta charset="UTF-8">

</head>
<style>
    div.a {
         text-align: center;
         background-color: red;
         width: 400px;
         padding: 0.0105px;;
     }
    div.b
    {
        width: auto; margin-left: auto; margin-right: auto; }
    }
</style>
<body>
<form style="background-color:red;height:40px;width:400px">
<div class="a">
    <h3 style="color:#ffffff;">
    Sở Thích Của Bạn
</h3>
</div>
</form>
<form style="background-color:whitesmoke;width:400px"">
<div name="b">
    <table>
    <tr>
        <td style="color:blue">Học và tên</td>
        <td><label><input type="text"name="hoten"</label></td>
    </tr>
    <tr>
        <td style="color:blue">Email</td>
        <td><label><input type="text"name="email"</label></td>
    </tr>
    <tr>
        <td style="color:blue">Sở thích</td>
        <td>
        <table>
            <tr>
        <td style="color:orange">
            <label><input type="checkbox" name="hobby">Thể thao</label>
        </td>
        <td style="color:orange">
            <label><input type="checkbox" name="hobby">Âm nhạc</label>
        </td>
        <td style="color:orange">
            <label>
                <input type="checkbox" name="hobby">Đọc sách</label>
        </td>
            </tr>
            <tr style="color:orange">
                <td><label><input type="checkbox" name="hobby">Lướt web</label></td>
                <td>
                    <label>
                    <input type="checkbox" name="hobby">Học kiến thức mới</label></td>
                <td><label><input type="checkbox" name="hobby">Điện ảnh</label></td>
            </tr>
            <tr>
                <td style="color:orange">
                    <label><input type="checkbox" name="hobby">Du lịch</label>
                </td>
            </tr>
    <tr>
        <table>
            <tr>
                <td>
                    <input type="button" name="submit" value="Gửi thông tin"/>
                </td>
                <td>
                    <input type="reset" value = "Nhập lại" />
                </td>
            </tr>
        </table>
            </tr>
        </table>
    </table>
</div>
</form>
</body>
</html>