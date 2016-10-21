
# 根据id修改用户信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/updateInfo

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 id | 是 | 字符串 | 
 name | 是 | 字符串 | 
 avator | 是 | 字符串 | 
 sex | 是 | 字符串 | 
 local | 是 | 字符串 | 
 realName | 是 | 字符串 | 
 examType | 是 | 字符串 | 关注领域
 descript | 是 | 字符串 | 

###返回结果示例

```javascript
  {
  	"message":"成功",
  	"data":true,
  	"apicode":10000
  }



```
