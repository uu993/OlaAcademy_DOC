# 错题集列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getWrongList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 type | 是 | 字符串 | 1 考点 2 真题 3 模考
 subjectType | 是 | 字符串 | 1 数学 2 英语 3 逻辑 4 写作
 userId | 是 | 字符串 | 
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "id": 9,
            "name": "2017年联考数学终极预测卷一",
            "subAllNum": 25,
            "wrongNum": 4
        },
        {
            "id": 10,
            "name": "2017年联考数学终极预测卷二",
            "subAllNum": 25,
            "wrongNum": 4
        },
        {
            "id": 11,
            "name": "2017年联考数学终极预测卷三",
            "subAllNum": 25,
            "wrongNum": 0
        },
        {
            "id": 12,
            "name": "2017年联考数学终极预测卷四",
            "subAllNum": 25,
            "wrongNum": 0
        },
        {
            "id": 13,
            "name": "2017年联考数学终极预测卷五",
            "subAllNum": 25,
            "wrongNum": 0
        },
        {
            "id": 14,
            "name": "2017年联考数学终极预测卷六",
            "subAllNum": 25,
            "wrongNum": 0
        },
        {
            "id": 15,
            "name": "2017年联考数学终极预测卷七",
            "subAllNum": 25,
            "wrongNum": 0
        },
        {
            "id": 16,
            "name": "2017年联考数学终极预测卷八",
            "subAllNum": 25,
            "wrongNum": 0
        }
    ],
    "apicode": 10000
}
