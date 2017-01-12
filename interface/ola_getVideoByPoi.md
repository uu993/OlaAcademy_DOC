# 获取课程知识点对应的视频
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getVideoByPoi

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pointId | 是 | 字符串 | 课程知识点id
 userId | 否 | 字符串 | userId
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": {
        "pointId": "55",
        "isCollect": "0",
        "playIndex": "1",
        "playProgress": "00:02:01",
        "videoList": [
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/01_jichu_01_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 21,
                "isfree": 1,
                "name": "课时1：应用题解题方法",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 705,
                "size": "624.73 KB",
                "timeSpan": "0:02:24",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/02_lirun_01_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 22,
                "isfree": 0,
                "name": "课时2：利润问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 572,
                "size": "624.73 KB",
                "timeSpan": "0:08:01",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/03_bili_01_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 23,
                "isfree": 0,
                "name": "课时3：比和比例问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 677,
                "size": "624.73 KB",
                "timeSpan": "0:14:37",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/04_bili_02_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 24,
                "isfree": 0,
                "name": "课时4：比例定理的应用",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 272,
                "size": "624.73 KB",
                "timeSpan": "0:05:54",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/05_gongc_01_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 25,
                "isfree": 0,
                "name": "课时5：工程问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 297,
                "size": "624.73 KB",
                "timeSpan": "0:08:00",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/06_gongc_02_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 26,
                "isfree": 0,
                "name": "课时6：工程问题的应用",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 708,
                "size": "624.73 KB",
                "timeSpan": "0:04:14",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/07_luc_01_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 27,
                "isfree": 0,
                "name": "课时7：路程问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 577,
                "size": "624.73 KB",
                "timeSpan": "0:07:21",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/08_luc_02_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 28,
                "isfree": 0,
                "name": "课时8：路程问题的应用",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 911,
                "size": "624.73 KB",
                "timeSpan": "0:04:07",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/09_luc_03_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 29,
                "isfree": 0,
                "name": "课时9：顺水与逆水问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 361,
                "size": "624.73 KB",
                "timeSpan": "0:00:49",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/10_luc_04_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 30,
                "isfree": 0,
                "name": "课时10：顺水与逆水的应用",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 581,
                "size": "624.73 KB",
                "timeSpan": "0:13:18",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/11_luc_05_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 31,
                "isfree": 0,
                "name": "课时11：相对速度问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 734,
                "size": "624.73 KB",
                "timeSpan": "0:05:02",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/12_luc_06_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 32,
                "isfree": 0,
                "name": "课时12：相对速度的应用",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 144,
                "size": "624.73 KB",
                "timeSpan": "0:03:37",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/13_rongy_01_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 33,
                "isfree": 0,
                "name": "课时13：溶液问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 377,
                "size": "624.73 KB",
                "timeSpan": "0:15:43",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/14_rongy_02_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 34,
                "isfree": 0,
                "name": "课时14：混合问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 873,
                "size": "624.73 KB",
                "timeSpan": "0:04:16",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            },
            {
                "address": "http://olamath.ufile.ucloud.com.cn/2016yingyong/15_zhishu_01_480p.mp4",
                "attachmentId": 4,
                "content": "0.0M",
                "id": 35,
                "isfree": 0,
                "name": "课时15：植树问题",
                "orgname": "幂学",
                "pic": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
                "playCount": 568,
                "size": "624.73 KB",
                "timeSpan": "0:04:48",
                "tname": "何敬",
                "url": "http://cospdf.ufile.ucloud.com.cn/sx_2016/jcjy_2.pdf",
                "weight": ""
            }
        ]
    },
    "apicode": 10000
}

```
