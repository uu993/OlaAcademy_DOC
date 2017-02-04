

# 获取支付宝支付订单信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /pay/getAliOrderInfo

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
  type | 是 | 字符串 | 1 月度会员 2 年度会员 3 视频
 goodsId | 否 | 字符串 | goodsId |
 userId | 是 | 字符串 | userId |
 coin | 否 | 字符串 | 欧拉币抵扣，最多抵10% |

###返回结果示例

```javascript
{
    "message": "成功",
    "authInfo": {
        "email": "456",
        "id": 2,
        "name": "wechat1",
        "phone": "13512345669",
        "profile": "123",
        "status": 1,
        "userId": 381,
        "createTime": "2017-02-04 09:18:25"
    },
    "apicode": 10000
}
