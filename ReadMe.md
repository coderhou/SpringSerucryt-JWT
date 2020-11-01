## 学习JWT的使用
+ 登录时需要在请求参数中使用json格式的登录信息，JwtLoginFilter.attemptAuthentication()方法中可以更改请求参数的格式为键值对
+ 访问接口时，需要在header中authorization加入token

![image-20201101155726829](C:\Users\HouJun\AppData\Roaming\Typora\typora-user-images\image-20201101155726829.png)