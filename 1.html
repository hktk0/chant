<%@ page contentType="text/html;charset=UTF-8" language="java" isELIgnored="false" %>
<%@ page import="java.util.*" %>
<html>
<head>
    <title>Title</title>
</head>
<%--<script src="js/jquery.min.js"></script>--%>
<script src="https://libs.baidu.com/jquery/1.8.3/jquery.js"></script>
<script type="text/javascript">
    function submitForm() {
        var inputCode=$("#authCode").attr("value");
        var list={"inputCode":inputCode};
        $.ajax({
            //请求方式
            type : "POST",
            //请求的媒体类型
            contentType: "application/x-www-form-urlencoded",
            //请求地址
            url : "auth/checkCode",
            //数据，json字符串
            data :list,
            dataType:"json",
            //请求成功
            success : function(result) {
                alert(result);
                if(result=="1"){
                    alert("验证通过");
                }else{
                    alert("验证失败，重新刷新验证码");
                    flushAuthCode();
                }
            },
            //请求失败，包含具体的错误信息
            error : function(e){
                alert(e.responseText);
            }
        });
    }
    function flushAuthCode() {
        //重新刷新验证码
        $("#codeImage").attr("src","auth/authCode?abc="+Math.random());
    }

</script>
<body>

    <form id="authForm" action="checkCode">
        <input type="text" id="authCode" name="authCode">
        <img type="image" src="auth/authCode" id="codeImage" name="codeImage" style="cursor:pointer;"/>
        <button type="button" id="submitBtn" name="submitBtn" value="提交" onclick="submitForm()"/>
    </form>
</body>
</html>
