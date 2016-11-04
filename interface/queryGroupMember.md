# 群成员列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /homework/queryGroupMember

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 groupId | 是 | 字符串 |
 pageIndex | 否 | 字符串 |
 pageSize | 否 | 字符串 |

###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "id": 3250,
            "name": "小欧8680",
            "sex": null,
            "age": 0,
            "phone": null,
            "passwd": null,
            "email": null,
            "birthday": null,
            "qq": null,
            "local": null,
            "regtime": null,
            "logintime": null,
            "avator": "default.jpg",
            "sign": null,
            "level": null,
            "honor": null,
            "learntime": null,
            "status": null,
            "examtype": null,
            "yzm": null,
            "isActive": 0,
            "realName": null,
            "coin": null,
            "vipTime": null
        },
        {
            "id": 3242,
            "name": "小欧2951",
            "sex": null,
            "age": 0,
            "phone": null,
            "passwd": null,
            "email": null,
            "birthday": null,
            "qq": null,
            "local": null,
            "regtime": null,
            "logintime": null,
            "avator": "default.jpg",
            "sign": null,
            "level": null,
            "honor": null,
            "learntime": null,
            "status": null,
            "examtype": null,
            "yzm": null,
            "isActive": 0,
            "realName": null,
            "coin": null,
            "vipTime": null
        }
    ],
    "apicode": 10000
}
