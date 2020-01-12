# 接口文档

- 注册接口
1. 请求URL：http://localhost:3000/api/sign-up
2. 请求方式：POST
3. |参数名|类型|是否必选|说明|
   |------|----|-------|----|
   |usernumber|string|Y|用户手机号|
   |password|string|Y|用户密码|
4. 返回实列
 ```js
   {
     code:1, //1代表注册成功，0代表注册失败
     meg:"返回成功或者失败的信息"
   }
 ```
