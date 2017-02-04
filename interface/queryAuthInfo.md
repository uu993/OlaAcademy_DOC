

# 获取认证信息及状态
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /auth/queryAuthInfo

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | userId |

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
        "domain": "数学",
        "status": 1,
        "userId": 381,
        "createTime": "2017-02-04 09:18:25"
    },
    "apicode": 10000
}
