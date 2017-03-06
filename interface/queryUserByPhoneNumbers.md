# 添加评论
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /comment/addComment

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 
 postId | 是 | 字符串 |  课程Id 或 帖子Id
 toUserId | 否 | 字符串 | 
 content | 否 | 字符串 | 
 imageIds | 否 | 字符串 |
 videoUrls | 否 | 字符串 |
 videoImgs | 否 | 字符串 |
 audioUrls | 否 | 字符串 |
 location | 否 | 字符串 | 
 type | 否 | 字符串 |   1 课程评论 2 帖子评论
 
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
