# No.1days
第一天上传GitHub
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>表单</title>
    <script type="text/javascript">
        var isShow=true;
        function change(){
            var v=document.getElementById("ps");
            if (isShow) {
                v.type="text";
                isShow=false;
            }else{
                v.type="password";
                isShow=true;
            }
        };
    </script>
</head>
<form>
 用户名：
<input type="text">
    <br/>
密码：
<input type="password" id="ps">
    <!--password为密码，即输入字符隐藏-->
</form>
<body>
<button onclick="change()">显示密码</button>
</body>
<form>
    <br/>
    你喜欢的水果有哪些？
    <br/>
    苹果<input type="checkbox">
    特麻头<input type="checkbox">
    香蕉<input type="checkbox">
    <!--复选框可以我全都要(即为多选）checkbox为复选框-->
    <br/>
    请选择您的性别：
    男<input type="radio" name="sex">
    女<input type="radio" name="sex">
    非男非女<input type="radio" name="sex">
    可男可女<input type="radio" name="sex">
    <br/>
    请选择您常用的网站
    <select>
        <option>www.baidu.com</option>
        <option>www.uc123.com</option>
        <option>www.bilibili.com</option>

    </select>
    <input type="button" value="按钮">
    <input type="submit" value="确定">
</form>
<body>

        <textarea cols="30" rows="30">请在此填写个人形象</textarea>
</body>
</html>
