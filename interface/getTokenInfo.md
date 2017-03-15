
# 用户登录token信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /token/getTokenInfo

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | userId

###返回结果示例

```javascript
  {
    "message": "成功",
    "result": {
        "id": 0,
        "userId": 381,
        "token": 15311450124
    },
    "apicode": 10000
}



```
