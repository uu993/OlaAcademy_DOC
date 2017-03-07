# 粉丝列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /attention/queryFollowerList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 |
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "id": 381,
            "name": "欧拉技术支持",
            "phone": "13581574730",
            "avator": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
            "sign": "123"
        }
    ],
    "apicode": 10000
}
