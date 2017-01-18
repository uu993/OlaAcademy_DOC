
# 后台获取VIP价格
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /pay/getVIPPrice

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": {
        "monthPrice": 38,
        "halfYearPrice": 198,
        "yearPrice": 298
    },
    "apicode": 10000
}
