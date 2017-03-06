# 根据手机号查询用户信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/queryUserByPhoneNumbers

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 phones | 是 | 字符串 | 多个用,分割
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "sign": "",
            "id": 754,
            "phone": "18500375369",
            "avator": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
            "name": "微何"
        },
        {
            "sign": "",
            "name": "Forever",
            "avator": "http://qzapp.qlogo.cn/qzapp/1105343675/F9B2D009F57C1FFA6ECFA2A5379C967C/100",
            "id": 2830,
            "phone": "13581574738"
        }
    ],
    "apicode": 10000
}
