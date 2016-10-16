
# （老师版）学生作业完成情况
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /homework/getHomeworkStatistics

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 groupId | 是 | 字符串 | groupId
 homeworkId | 是 | 字符串 | homeworkId
 pageIndex | 是 | 字符串 | 起始页 1
 pageSize | 是 | 字符串 | 

###返回结果示例

```javascript
{
    "message": "成功",
    "result": {
        "unfinishedCount": 902,
        "finishedCount": 10,
        "correctness": 62,
        "statisticsList": [
            {
                "userId": 381,
                "userName": "小欧4738",
                "userAvatar": "1471223596772.jpg",
                "finished": 58
            },
            {
                "userId": 382,
                "userName": "小欧",
                "userAvatar": "default.jpg",
                "finished": 58
            },
            {
                "userId": 383,
                "userName": "小欧2034",
                "userAvatar": "default.jpg",
                "finished": 0
            },
            {
                "userId": 384,
                "userName": "小欧0270",
                "userAvatar": "default.jpg",
                "finished": 66
            },
        ]
    },
    "apicode": 10000
}
