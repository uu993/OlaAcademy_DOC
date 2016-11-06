
# 用户登录
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/login

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 phone | 是 | 字符串 | 手机号
 passwd | 是 | 字符串 | 密码

###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "optionName": "机构",
            "optionList": [
                {
                    "address": "http://www.mykepu.com:8080/pic/organization/1.jpg",
                    "attendCount": 951,
                    "checkinCount": 39,
                    "id": 1,
                    "logo": "http://commodity.ufile.ucloud.com.cn/logo1.jpg",
                    "name": "2017年幂学系统班",
                    "org": "由幂学教育提供",
                    "profile": "",
                    "type": 1
                },
                {
                    "address": "http://www.mykepu.com:8080/pic/organization/2.jpg",
                    "attendCount": 458,
                    "checkinCount": 27,
                    "id": 2,
                    "logo": "http://commodity.ufile.ucloud.com.cn/logo1.jpg",
                    "name": "2017年幂学私塾班",
                    "org": "由幂学教育提供",
                    "profile": "",
                    "type": 1
                },
                {
                    "address": "http://www.mykepu.com:8080/pic/organization/3.jpg",
                    "attendCount": 201,
                    "checkinCount": 19,
                    "id": 3,
                    "logo": "http://commodity.ufile.ucloud.com.cn/logo2.jpg",
                    "name": "2017年京虎系统班",
                    "org": "由京虎教育提供",
                    "profile": "",
                    "type": 1
                },
                {
                    "address": "http://www.mykepu.com:8080/pic/organization/3.jpg",
                    "attendCount": 0,
                    "checkinCount": 0,
                    "id": 4,
                    "logo": "http://commodity.ufile.ucloud.com.cn/logo2.jpg",
                    "name": "2017年京虎私塾班",
                    "org": "由京虎教育提供",
                    "profile": "",
                    "type": 1
                }
            ]
        },
        {
            "optionName": "学校",
            "optionList": []
        }
    ],
    "apicode": 10000
}
