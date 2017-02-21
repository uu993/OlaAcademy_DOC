
# 第三方登录
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/loginBySDK

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 source | 是 | 字符串 | 微信传值 wechat；   qq传值 QQ； 微博传值 sinaMicroblog
 sourceId | 是 | 字符串 |  qq 微博 的openId   微信 unionId
 
###返回结果示例

data 为空：未绑定手机号，前端进入绑定手机号页面  不为空：已绑定，登陆成功

```javascript
  {
    "message": "成功",
    "data": {
        "id": 0,
        "name": null,
        "sex": null,
        "age": 0,
        "phone": "15311450124",
        "passwd": "123123",
        "email": null,
        "birthday": null,
        "qq": null,
        "regtime": null,
        "logintime": 1445257362174,
        "avator": null,
        "sign": null,
        "level": null,
        "honor": null,
        "learntime": null,
        "status": null,
        "examtype": null,
        "yzm": null,
        "isActive": 1,   // 1 学生 2 老师
        "realName": null,
        "infoPerfectLev": null
    },
    "apicode": 10000
}



```
