# 个人主页
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /circle/getUserPostList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 |  userId
 
###返回结果示例
```javascript
{
    "message": "成功",
    "result": {
        "id": 381,
        "name": "欧拉技术支持",
        "avator": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
        "sign": "123",
        "deployList": [
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "测试结果表明的立场上",
                "courseId": 0,
                "id": 13613,
                "imageGids": "4c4deb5e-7059-45e7-afbe-1751ea5e05e9",
                "isPublic": 1,
                "location": "",
                "praiseNumber": 1,
                "readNumber": 29,
                "title": "测试",
                "type": 2,
                "userId": 381,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "videoId": 0,
                "time": "2016-12-11 10:45:04"
            }
        ],
        "replyList": [
            {
                "assignUser": "",
                "commentNumber": 0,
                "content": "路过咖啡厅，看见一个人在看视频学习，突然感觉好眼熟，仔细一看，原来是用欧拉联考学习",
                "courseId": 0,
                "id": 4233,
                "imageGids": "",
                "isPublic": 1,
                "location": "北京市朝阳区",
                "praiseNumber": 13,
                "readNumber": 17,
                "title": "路过咖啡厅，看见一个人在看视频学习，突然感觉好眼熟，仔细一看，原来是用欧拉联考学习",
                "type": 2,
                "userId": 381,
                "userName": "欧拉技术支持",
                "userAvatar": "78de30c6-2234-4ac0-af2d-0f0b5f792f91",
                "videoId": 0,
                "time": "2016-09-01 18:35:02"
            }
        ]
    },
    "apicode": 10000
}
