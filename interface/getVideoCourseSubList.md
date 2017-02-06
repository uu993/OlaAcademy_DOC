# 视频课程列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getVideoCourseSubList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pid | 是 | 字符串 | 父级课程Id
###返回结果示例

```javascript
{
    "message": "成功",
    "result": {
        "address": "http://cospic.ufile.ucloud.com.cn/1.jpg",
        "bannerPic": "",
        "id": 34,
        "isBanner": 0,
        "name": "导学课程",
        "pid": "1",
        "playcount": 114,
        "profile": "",
        "subAllNum": 2,
        "teacherId": "1",
        "totalTime": "",
        "type": "2",
        "teacherName": "陈剑",
        "teacherAvator": "http://upload.swiftacademy.cn:8080/swift/teacher/avatar1.jpg",
        "subList": [
            {
                "address": "http://cospic.ufile.ucloud.com.cn/31.jpg",
                "bannerPic": "http://banner.ufile.ucloud.com.cn/course_banner4.jpg",
                "id": 188,
                "isBanner": 1,
                "name": "2017年最新数学考试大纲解析",
                "pid": "34",
                "playcount": 4099,
                "profile": "",
                "subAllNum": 1,
                "teacherId": "1",
                "totalTime": "40分钟",
                "type": "2"
            },
            {
                "address": "http://cospic.ufile.ucloud.com.cn/30.jpg",
                "bannerPic": "http://banner.ufile.ucloud.com.cn/banner6.jpg",
                "id": 189,
                "isBanner": 0,
                "name": "2017年最新逻辑考试大纲解析",
                "pid": "34",
                "playcount": 2178,
                "profile": "",
                "subAllNum": 1,
                "teacherId": "1",
                "totalTime": "44分钟",
                "type": "2"
            },
            {
                "address": "http://cospic.ufile.ucloud.com.cn/28.jpg",
                "bannerPic": "",
                "id": 191,
                "isBanner": 0,
                "name": "考研英语(二)备考总攻略",
                "pid": "34",
                "playcount": 812,
                "profile": "",
                "subAllNum": 4,
                "teacherId": "1",
                "totalTime": "33分钟",
                "type": "2"
            },
            {
                "address": "http://cospic.ufile.ucloud.com.cn/3.jpg",
                "bannerPic": "",
                "id": 214,
                "isBanner": 0,
                "name": "2017年最新写作考试大纲解析",
                "pid": "34",
                "playcount": 264,
                "profile": "",
                "subAllNum": 1,
                "teacherId": "1",
                "totalTime": "34分钟",
                "type": "2"
            }
        ]
    },
    "apicode": 10000
}
