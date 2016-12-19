
# 点赞列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /circle/getPraiseList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 用户Id
 praiseId | 否 | 字符串 | 最后一条ID，用户翻页
 pageSize | 否 | 字符串 | 
###返回结果示例

```javascript
{
	"message": "成功",
	"result": [{
		"praiseId": 3,
		"postId": "13616",
		"userId": "754",
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"time": "2016-12-19 12:05:50",
		"isRead": 1
	}],
	"apicode": 10000
}
