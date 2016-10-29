# 欧拉圈列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /circle/getCircleList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 circleId | 否 | 字符串 | 当前页最后一条的id
 pageSize | 否 | 字符串 | 每页条数
 type | 否 | 字符串 | 1 学习记录 2 帖子 "" 全部
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "id": 49,
            "size": "662K",
            "title": "论说文经典素材之仁德篇（田然独家提供）",
            "type": 4,
            "url": "http://datapdf.ufile.ucloud.com.cn/write/x_7.pdf",
            "time": "2016-10-29 05:01:20"
        },
        {
            "id": 48,
            "size": "690K",
            "title": "论说文经典素材之权衡篇（田然独家提供）",
            "type": 4,
            "url": "http://datapdf.ufile.ucloud.com.cn/write/x_6.pdf",
            "time": "2016-10-29 04:01:20"
        },
        {
            "id": 47,
            "size": "715K",
            "title": "论说文经典素材之理想篇（田然独家提供）",
            "type": 4,
            "url": "http://datapdf.ufile.ucloud.com.cn/write/x_5.pdf",
            "time": "2016-10-29 03:01:20"
        },
        {
            "id": 46,
            "size": "589K",
            "title": "论说文经典素材之合作篇（田然独家提供）",
            "type": 4,
            "url": "http://datapdf.ufile.ucloud.com.cn/write/x_4.pdf",
            "time": "2016-10-29 02:01:20"
        },
        {
            "id": 45,
            "size": "680K",
            "title": "论说文经典素材之奉献篇（田然独家提供）",
            "type": 4,
            "url": "http://datapdf.ufile.ucloud.com.cn/write/x_3.pdf",
            "time": "2016-10-29 01:01:20"
        }
    ],
    "apicode": 10000
}
