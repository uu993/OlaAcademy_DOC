# 获取整套视频下的视频列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /goods/getVideoList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 gid | 是 | 字符串 | goodsId
 userId | 否 | 字符串 | userId
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "id": 110,
      "name": "课时1：算数部分【1】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/01_s_01.mp4",
      "playCount": 24,
      "timeSpan": "0.041585",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null,
      "attachmentId": 1,
      "url": "http://cospdf.ufile.ucloud.cn/lj_xuerui/xr_jc_1.pdf",
      "size": "710k"
    },
    {
      "id": 111,
      "name": "课时2：算数部分【2】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/02_s_02.mp4",
      "playCount": 12,
      "timeSpan": "0.059537",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null,
      "attachmentId": 1,
      "url": "http://cospdf.ufile.ucloud.cn/lj_xuerui/xr_jc_1.pdf",
      "size": "710k"
    },
    {
      "id": 112,
      "name": "课时3：算数部分【3】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/03_ss_03.mp4",
      "playCount": 10,
      "timeSpan": "0.057615",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null,
      "attachmentId": 1,
      "url": "http://cospdf.ufile.ucloud.cn/lj_xuerui/xr_jc_1.pdf",
      "size": "710k"
    },
    {
      "id": 113,
      "name": "课时4：算数部分【4】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/04_ss_04.mp4",
      "playCount": 14,
      "timeSpan": "0.063981",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null,
      "attachmentId": 1,
      "url": "http://cospdf.ufile.ucloud.cn/lj_xuerui/xr_jc_1.pdf",
      "size": "710k"
    },
    {
      "id": 114,
      "name": "课时5：应用题部分【1】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/05_yy_01.mp4",
      "playCount": 20,
      "timeSpan": "0.054039",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null,
      "attachmentId": 1,
      "url": "http://cospdf.ufile.ucloud.cn/lj_xuerui/xr_jc_1.pdf",
      "size": "710k"
    },
    {
      "id": 115,
      "name": "课时6：应用题部分【2】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/06_yy_02.mp4",
      "playCount": 11,
      "timeSpan": "0.075138",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null
    },
    {
      "id": 116,
      "name": "课时7：应用题部分【3】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/07_yy_03.mp4",
      "playCount": 7,
      "timeSpan": "0.044525",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null,
      "attachmentId": 1,
      "url": "http://cospdf.ufile.ucloud.cn/lj_xuerui/xr_jc_1.pdf",
      "size": "710k"
    },
    {
      "id": 117,
      "name": "课时8：应用题部分【4】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/08_yy_04.mp4",
      "playCount": 6,
      "timeSpan": "0.057789",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null
    },
    {
      "id": 118,
      "name": "课时9：代数部分【1】",
      "content": null,
      "address": "http://olamath.ufile.ucloud.com.cn/2016jc/09_ds_01.mp4",
      "playCount": 7,
      "timeSpan": "0.059618",
      "weight": null,
      "orgname": null,
      "tname": null,
      "isBanner": 0,
      "pic": null,
      "attachmentId": 1,
      "url": "http://cospdf.ufile.ucloud.cn/lj_xuerui/xr_jc_1.pdf",
      "size": "710k"
    }
  ],
  "apicode": 10000
}
