# 发布作业
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /homework/deployHomework

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 groupId | 是 | 字符串 | 
 name | 是 | 字符串 | 
 subjectId | 否 | 字符串 | 题目Id串 逗号分隔
 
 ```javascript
{
    "message": "成功",
    "apicode": 10000
}
