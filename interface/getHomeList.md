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
        "bannerList": [
            {
                "id": 2,
                "name": "",
                "objectId": 0,
                "pic": "",
                "type": 2,
                "url": ""
            },
            {
                "id": 1,
                "name": "",
                "objectId": 0,
                "pic": "",
                "type": 1,
                "url": "",
                "commodity": {
                    "attentionnum": 100,
                    "detail": "逻辑名师，讲课生动有趣，善于把握考点，总结规律，把知识点板块化，把考点逻辑化，对考生的逻辑学习提升起到了至关重要的作用。学生评语：方法独特，一招制胜，把复杂的逻辑提干简单化，冗长的逻辑容易理解。",
                    "id": 17,
                    "image": "http://banner.ufile.ucloud.com.cn/logo_mx.png",
                    "leanstage": "8月17日-12月31日",
                    "name": "联考逻辑全程体系课程【饶思中】【限时】",
                    "org": "幂学教育出版社",
                    "paynum": 28,
                    "price": 98,
                    "status": 0,
                    "suitto": "教材版本：管理类联考综合能力历年真题",
                    "totaltime": 960,
                    "type": "1",
                    "url": "http://cospic.ufile.ucloud.com.cn/92.jpg",
                    "videonum": 12
                }
            }
        ],
        "questionList": [
            {
                "id": 5,
                "title": "56",
                "content": "sdf",
                "number": 2,
                "time": ""
            },
            {
                "id": 4,
                "content": "56",
                "number": 1,
                "time": ""
            }
        ],
        "goodsList": [
            {
                "attentionnum": 100,
                "detail": "对考试内容作全面细致的讲解,温故知新。",
                "id": 1,
                "image": "http://banner.ufile.ucloud.com.cn/logo_mx.png",
                "leanstage": "5月17日-12月31日",
                "name": "2017年数学周末班基础课程",
                "org": "幂学教育版权所有",
                "paynum": 939,
                "price": 1200,
                "status": 0,
                "suitto": "教材版本：《联考综合能力数学高分指南》",
                "totaltime": 2200,
                "type": "1",
                "url": "http://commodity.ufile.ucloud.com.cn/math.jpg",
                "videonum": 27
            },
            {
                "attentionnum": 100,
                "detail": "掌握主要复习要点，确保能够达到考试优良水平",
                "id": 2,
                "image": "http://banner.ufile.ucloud.com.cn/logo_mx.png",
                "leanstage": "5月17日-12月31日",
                "name": "2016年数学真题密训班课程",
                "org": "幂学教育版权所有",
                "paynum": 323,
                "price": 1000,
                "status": 0,
                "suitto": "教材版本：《数学历年真题名家详解》",
                "totaltime": 1980,
                "type": "1",
                "url": "http://commodity.ufile.ucloud.com.cn/math.jpg",
                "videonum": 24
            }
        ]
    },
    "apicode": 10000
}
