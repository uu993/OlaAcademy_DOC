# 欧拉币获取及消耗明细
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /coin/getHistoryList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 
 
 ```javascript
{
    "message": "成功",
    "result": [
        {
            "id": 17,
            "userId": 381,
            "name": "每日签到",
            "type": 1,
            "dealNum": 5,
            "date": "2016-10-18"
        },
        {
            "id": 16,
            "userId": 381,
            "name": "解锁题目",
            "type": 6,
            "dealNum": -20,
            "date": "2016-10-18"
        },
        {
            "id": 15,
            "userId": 381,
            "name": "首次购买课程赠送",
            "type": 5,
            "dealNum": 150,
            "date": "2016-10-18"
        },
        {
            "id": 14,
            "userId": 381,
            "name": "购买课程抵用",
            "type": 7,
            "dealNum": -120,
            "date": "2016-10-18"
        },
        {
            "id": 13,
            "userId": 381,
            "name": "首次购买会员",
            "type": 4,
            "dealNum": 100,
            "date": "2016-10-18"
        },
        {
            "id": 5,
            "userId": 381,
            "name": "每日签到",
            "type": 2,
            "dealNum": 0,
            "date": "2016-09-23"
        },
        {
            "id": 1,
            "userId": 381,
            "name": "每日签到",
            "type": 1,
            "dealNum": 0,
            "date": "2016-09-21"
        }
    ],
    "apicode": 10000
}
