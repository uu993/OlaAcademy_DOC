# 首页列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /home/getHomeList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 否 | 字符串 |  | | 
 
###返回结果示例

```javascript

{
    "message": "成功",
    "result": {
        "studyDay": "3",
        "finishCount": 28,
        "defeatPercent": "34%",
        "bannerList": [
            {
                "id": 3,
                "name": "学校",
                "objectId": "2,2",
                "pic": "http://banner.ufile.ucloud.com.cn/steet.jpg",
                "type": 4,
                "url": ""
            },
            {
                "id": 1,
                "name": "面试",
                "objectId": "246",
                "pic": "http://cospic.ufile.ucloud.com.cn/201715.jpg",
                "type": 2,
                "url": ""
            },
            {
                "id": 2,
                "name": "笔试",
                "objectId": "188",
                "pic": "http://cospic.ufile.ucloud.com.cn/banner01.png",
                "type": 2,
                "url": ""
            }
        ],
        "questionList": [
            {
                "id": 33598,
                "title": "不能没有你",
                "content": "刚才怎么都打不开网页，太不爽了，才发现没有这个软件都不会学习了……这么快就依赖上你了",
                "number": 57,
                "time": "2017-01-14 22:55:12"
            },
            {
                "id": 33535,
                "title": "终于快过年了",
                "content": "2016年真的是在一线生鸡中见缝插鸡，哈哈",
                "number": 38,
                "time": "2017-01-13 23:41:52"
            }
        ],
        "goodsList": [
            {
                "attentionnum": 100,
                "createTime": {
                    "date": 5,
                    "day": 1,
                    "hours": 9,
                    "minutes": 18,
                    "month": 11,
                    "seconds": 27,
                    "time": 1480900707000,
                    "timezoneOffset": -480,
                    "year": 116
                },
                "detail": "逻辑名师，讲课生动有趣，善于把握考点，总结规律，把知识点板块化，把考点逻辑化，对考生的逻辑学习提升起到了至关重要的作用。学生评语：方法独特，一招制胜，把复杂的逻辑提干简单化，冗长的逻辑容易理解。",
                "id": 17,
                "image": "http://cospic.ufile.ucloud.com.cn/teacher/rsz.jpg",
                "leanstage": "8月17日-12月31日",
                "name": "饶思中讲逻辑之全程体系课程",
                "org": "饶思中",
                "paynum": 60,
                "price": 98,
                "status": 0,
                "suitto": "教材版本：管理类联考综合能力历年真题",
                "totaltime": 960,
                "type": "1",
                "url": "http://cospic.ufile.ucloud.com.cn/201701.jpg",
                "videonum": 12
            },
            {
                "attentionnum": 100,
                "createTime": {
                    "date": 4,
                    "day": 0,
                    "hours": 22,
                    "minutes": 52,
                    "month": 11,
                    "seconds": 6,
                    "time": 1480863126000,
                    "timezoneOffset": -480,
                    "year": 116
                },
                "detail": "本课程以十二年真题解析为基点，庖丁解牛剖析，洞察命题新动向，指导考生把握命题脉搏，赢取高分。对真题进行了科学的分类和精讲，先按模块将知识点“画龙”，随后逐题“解析、点睛、技巧、扩展”并分层次深度剖析，将考点与方法技巧进行有机联系，不仅彰显了命题轨迹和应试精髓，更达到了居高临下和立竿见影之功效。对考试中常考的题型和重点做更进一步的讲解，培养考生的数学考试思想和思维模式，尤其重视解题技巧的训练，以便考生更系统、更宏观的掌握数学思想，提高分数。",
                "id": 19,
                "image": "http://cospic.ufile.ucloud.com.cn/teacher/cj.jpg",
                "leanstage": "冲刺阶段",
                "name": "陈剑讲数学之十二年真题精讲（一）",
                "org": "陈剑",
                "paynum": 21,
                "price": 120,
                "status": 0,
                "suitto": "教材版本：《数学历年真题名家详解》",
                "totaltime": 354,
                "type": "1",
                "url": "http://cospic.ufile.ucloud.com.cn/201702.png",
                "videonum": 4
            }
        ],
        "courseList": [
            {
                "address": "http://cospic.ufile.ucloud.com.cn/201708.png",
                "bannerPic": "http://banner.ufile.ucloud.com.cn/course_banner7.jpg",
                "id": 188,
                "isBanner": 1,
                "name": "2017年最新数学考试大纲解析",
                "pid": "34",
                "playcount": 7688,
                "profile": "",
                "subAllNum": 1,
                "totalTime": "40分钟",
                "type": "2"
            },
            {
                "address": "http://cospic.ufile.ucloud.com.cn/201704.jpg",
                "bannerPic": "",
                "id": 249,
                "isBanner": 0,
                "name": "MPAcc复试课程（三）",
                "pid": "245",
                "playcount": 58,
                "profile": "",
                "subAllNum": 5,
                "totalTime": "70分钟",
                "type": "2"
            }
        ]
    },
    "apicode": 10000
}
