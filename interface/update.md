
# 根据id修改用户信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/updateInfo

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 id | 是 | 字符串 | 用户id
   @RequestParam(value = "id", required = false) String id,
			@RequestParam(value = "name", required = false) String name,
			@RequestParam(value = "avator", required = false) String avator,
			@RequestParam(value = "sex", required = false) String sex,
			@RequestParam(value = "local", required = false) String local,
			@RequestParam(value = "realName", required = false) String realName,
			@RequestParam(value = "examType", required = false) String examType,
			@RequestParam(value = "descript", required = false) String descript

###返回结果示例

```javascript
  {
  	"message":"成功",
  	"data":true,
  	"apicode":10000
  }



```
