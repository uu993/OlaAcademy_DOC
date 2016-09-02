
# 学生所在群及可加入的群列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /homework/getUserGroupList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 
 type | 是 | 字符串 |  1 数学 2 英语 3 逻辑 4 写作
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "avatar": "Forever群",
            "createUser": 381,
            "id": 2,
            "name": "Forever群",
            "profile": "",
            "type": 1,
            "time": "2016-08-31 00:00",
            "isMember": 1,
            "number": 1
        }
    ],
    "apicode": 10000
}
