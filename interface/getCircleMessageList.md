
# 评论消息列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /comment/getCircleMessageList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 用户Id
 commentId | 否 | 字符串 | 最后一条ID，用户翻页
 pageSize | 否 | 字符串 | 
 type | 是 | 字符串 | 1 观看记录 2 发帖 ，固定传2
###返回结果示例

```javascript
{
	"message": "成功",
	"result": [{
		"commentId": 259,
		"postId": 13616,
		"userId": 1292,
		"userName": "明哥",
		"userAvatar": "1474529387314.gif",
		"location": "",
		"content": "说话",
		"audioUrls": "movie/2016/12/15/64dcac1f-d3c5-4b75-ab4d-09def63ea977.amr",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-15 13:58:30"
	}, {
		"commentId": 253,
		"postId": 13616,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "",
		"imageIds": "",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "movie/2016/12/13/ff288981-da3d-424c-86d8-39312ad33861.mp3",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-13 15:30:48"
	}, {
		"commentId": 252,
		"postId": 13616,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "",
		"imageIds": "973c9f64-e896-462e-8d46-e6ecc46a456f",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-13 15:29:57"
	}, {
		"commentId": 251,
		"postId": 13616,
		"userId": 1292,
		"userName": "明哥",
		"userAvatar": "1474529387314.gif",
		"location": "",
		"content": "自言自语",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-13 14:28:15"
	}, {
		"commentId": 250,
		"postId": 13616,
		"userId": 1292,
		"userName": "明哥",
		"userAvatar": "1474529387314.gif",
		"location": "",
		"content": "他现在",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-13 14:28:08"
	}, {
		"commentId": 249,
		"postId": 13616,
		"userId": 1292,
		"userName": "明哥",
		"userAvatar": "1474529387314.gif",
		"location": "",
		"content": "擒贼先擒王",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-13 14:24:29"
	}, {
		"commentId": 248,
		"postId": 13616,
		"userId": 1292,
		"userName": "明哥",
		"userAvatar": "1474529387314.gif",
		"location": "",
		"content": "阿德",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-13 14:24:21"
	}, {
		"commentId": 245,
		"postId": 13610,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "",
		"videoUrls": "movie/2016/12/13/8e957ac1-b870-4404-80e8-d7a91a568f7e.mp4",
		"videoImgs": "movie/2016/12/13/8e957ac1-b870-4404-80e8-d7a91a568f7e.jpg",
		"audioUrls": "",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-13 11:17:40"
	}, {
		"commentId": 237,
		"postId": 13616,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "你",
		"imageIds": "",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "movie/2016/12/12/38946cff-b90f-4b83-8b21-1a06dd62e342.mp3",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-12 17:04:01"
	}, {
		"commentId": 236,
		"postId": 13616,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "我",
		"imageIds": "",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "movie/2016/12/12/a547537f-b42c-4091-8f72-0ca1ac118d5b.m4a",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-12 14:14:11"
	}, {
		"commentId": 235,
		"postId": 13616,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "movie/2016/12/12/f9a142d3-2471-4fb8-b344-22beca83d82f.m4a",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-12 14:12:52"
	}, {
		"commentId": 231,
		"postId": 13610,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "",
		"videoUrls": "movie/2016/12/10/c7f4407d-f87f-4058-a83c-acd6fcd25553.mp4",
		"videoImgs": "movie/2016/12/10/c7f4407d-f87f-4058-a83c-acd6fcd25553.jpg",
		"audioUrls": "",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-10 11:17:16"
	}, {
		"commentId": 230,
		"postId": 13610,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "movie/2016/12/10/d79f173b-1175-42c1-b2da-f1c45a6eadc1.mp3",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-10 11:16:03"
	}, {
		"commentId": 227,
		"postId": 13610,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "",
		"videoUrls": "movie/2016/12/07/bb8077d7-854c-4a54-9f00-e70de5682fe2.mp4",
		"videoImgs": "movie/2016/12/07/bb8077d7-854c-4a54-9f00-e70de5682fe2.jpg",
		"audioUrls": "",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-07 16:47:02"
	}, {
		"commentId": 226,
		"postId": 13610,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "movie/2016/12/08/881b6cc2-7c65-4557-8692-b31861099acd.mp3",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-07 16:46:02"
	}, {
		"commentId": 225,
		"postId": 13610,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "movie/2016/12/08/881b6cc2-7c65-4557-8692-b31861099acd.mp3",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-07 16:46:02"
	}, {
		"commentId": 224,
		"postId": 13610,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "b8f9f33c-fb18-4509-8be3-15d9eb6ba4a2",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-07 16:41:52"
	}, {
		"commentId": 223,
		"postId": 13610,
		"userId": 754,
		"userName": "微何",
		"userAvatar": "1c84834c-1d69-47fb-a009-f426c6ec6d83",
		"location": "北京市,海淀区",
		"content": "测试",
		"imageIds": "b343bedf-857a-4b4e-a170-7d75e25fb932,5754ae55-7866-4a76-8aeb-8a5732cdcac2",
		"videoUrls": "",
		"videoImgs": "",
		"audioUrls": "",
		"praiseNumber": 0,
		"isRead": 1,
		"time": "2016-12-07 13:48:41"
	}, {
		"commentId": 118,
		"postId": 6796,
		"userId": 1777,
		"userName": "小欧5666",
		"userAvatar": "default.jpg",
		"location": "北京市,海淀区",
		"toUserId": "381",
		"toUserName": "欧拉技术支持",
		"content": "哦，看到了，确实看不清",
		"praiseNumber": 0,
		"isRead": 0,
		"time": "2016-09-20 20:43:37"
	}, {
		"commentId": 76,
		"postId": 4233,
		"userId": 517,
		"userName": "欧拉小助手",
		"userAvatar": "59ba012f-c2d3-4564-889d-76b80c8daef4",
		"location": "北京市,海淀区",
		"toUserId": "381",
		"toUserName": "欧拉技术支持",
		"content": "赞",
		"praiseNumber": 0,
		"isRead": 0,
		"time": "2016-09-05 15:02:31"
	}],
	"apicode": 10000
}
