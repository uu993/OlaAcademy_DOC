# 资料列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /circle/getMaterailList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 materailId | 否 | 字符串 | 当前页最后一条的id
 pageSize | 否 | 字符串 | 每页条数
 type | 否 | 字符串 | 1 数学 2 英语 3 逻辑 4 写作
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "id": 10,
            "pic": "http://cospic.ufile.ucloud.com.cn/icon.jpg",
            "price": "20",
            "provider": "欧拉学院",
            "size": "813K",
            "title": "平面几何精选20题",
            "type": 1,
            "url": "http://datapdf.ufile.ucloud.com.cn/math/s_10.pdf",
            "time": "2016-09-22 10:01:20"
        },
        {
            "id": 9,
            "pic": "http://cospic.ufile.ucloud.com.cn/icon.jpg",
            "price": "20",
            "provider": "欧拉学院",
            "size": "607K",
            "title": "蒙猜大法－数学条件充分性判断终极解题技巧",
            "type": 1,
            "url": "http://datapdf.ufile.ucloud.com.cn/math/s_9.pdf",
            "time": "2016-09-21 10:01:20"
        },
        {
            "id": 8,
            "pic": "http://cospic.ufile.ucloud.com.cn/icon.jpg",
            "price": "0",
            "provider": "欧拉学院",
            "size": "772K",
            "title": "管理类联考数学必备公式",
            "type": 1,
            "url": "http://datapdf.ufile.ucloud.com.cn/math/s_8.pdf",
            "time": "2016-09-20 10:01:20"
        }
    ],
    "apicode": 10000
}
