# 获取今日签到状态
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /dailyact/getCheckinStatus

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 |  
 
 ```javascript
###返回结果示例
{
    "message": "成功",
    "result": {
        "status": 0,
        "lastSignIn": "2016-12-23",
        "signInDays": "1",
        "coin": "385",
        "profileTask": 1,
        "vipTask": 1,
        "courseTask": 1,
        "todayCoin": 0,
        "courseBuyNum": 7,
        "courseCollectNum": 5
    },
    "apicode": 10000
}
