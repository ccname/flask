
### 获取用户信息

#### 请求
ssssss
    GET /user/user/

##### params
    id int 用户id

#### 响应

成功响应：
{
  "code": 200,
  "data": {
    "avatar": "upload\\QQ\u56fe\u7247.png",
    "id": 1,
    "name": "rose",
    "phone": "18879090770"
  }
}
失败响应：

    {
        'code': 0,
        'msg': '数据库错误，请稍后重试'
    }
