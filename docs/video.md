RestFul 接口地址: `http://47.106.220.143`

全局`code`为状态码 0 为成功 其余都是失败 返回的提示信息都是中文

返回视频资源地址集合:

请求方式:`get`

请求路由:`/videos`

请求参数：无

请求示例 : `http://47.106.220.143/videos`

返回响应：`{code:0或1,data: 视频资源地址数组}`

---

请求单个视频资源地址:

请求方式:`get`

请求路由:`/video`

请求参数：无

请求示例 : `http://47.106.220.143/video/1.mp4`

返回响应：对应的短视频资源

---