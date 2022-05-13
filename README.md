<div align = "center">表1  测试注册功能</div>
<table width="100%">
	<tr>
	    <td>项目/软件</td><td>Campus_shops</td><td>开发环境</td> <td colspan="3">JAVA</td> 
	</tr>
    <tr>
	    <td>功能模块名</td> <td>register</td><td>编制人</td> <td colspan="3">祝世雷</td> 
	</tr>
    <tr>
	    <td>用例编号</td>	    <td>AD-008</td>	    <td>时间</td>       <td colspan="3">2022.5</td> 
	</tr>
    <tr>
	    <td>功能模块说明</td>    <td colspan="5">注册功能</td>
	</tr>
    <tr>
	    <td>测试说明</td>    <td colspan="5">测试注册函数：ResultVo userReg(@RequestBody UserInfo userInfo, HttpSession session) </td>
	</tr>
    <tr>
	    <td>预置条件</td>    <td colspan="5">前端后端服务已开启，注册页面已打开</td>
	</tr>
    <tr>
	    <td>测试人员</td>    <td colspan="5">祝世雷</td>
	</tr>
    <tr>
	    <td>测试编号</td> <td>操作描述</td><td>输入数据</td>  <td>期望结果</td> <td>实际结果</td> <td>测试状态</td> 
	</tr >
    <tr>
	    <td>1</td>
	    <td>输入未注册的手机号等信息并点击获取验证码</td>
	    <td>Username,Password,Vercode</td>  
        <td>前端返回验证码发送成功，控制台返回成功信息</td> 
        <td>前端返回验证码发送成功，控制台返回成功信息</td> 
        <td>P</td> 
	</tr >
    <tr>
	    <td>2</td>
	    <td>输入已经注册过的手机及其他信息</td>
	    <td>Username,Password,Vercode</td>  
        <td>前端提示该手机号已经注册过了，控制台返回错误代码</td> 
        <td>前端提示该手机号已经注册过了，控制台返回错误代码</td> 
        <td>P</td> 
	</tr >
    <tr>
	    <td>3</td>
	    <td>输入错误的验证码并提交注册</td>
	    <td>Username,Password,Vercode</td>  
        <td>前端提示验证码错误，控制台返回错误代码</td> 
        <td>前端提示验证码错误，控制台返回错误代码</td> 
        <td>P</td> 
	</tr >
    <tr>
	    <td>4</td>
	    <td>输入争取的验证码并提交注册</td>
	    <td>Username,Password,Vercode</td>  
        <td>前端注册成功待审核，控制台返回错误代码</td> 
        <td>前端注册成功待审核，控制台返回错误代码</td> 
        <td>P</td> 
	</tr >
    <tr>
	    <td>5</td>
	    <td>输入错误的邮箱格式，密码格式等</td>
	    <td>Username,Password,Vercode</td>  
        <td>前端提示相应的格式错误，控制台返回错误代码</td> 
        <td>前端提示相应的格式错误，控制台返回错误代码</td> 
        <td>P</td> 
	</tr >
</table>
