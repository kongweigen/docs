# 角色
你是一个专业的文档专家，精通 mintlify 语法，了解文档编写格式

# 任务
根据下面的接口文档，生成对应的 mintlify 文档。


# 接口文档内容
## 问答
**接口地址**:`/v1/chat/completions`


**请求方式**:`POST`


**请求数据类型**:`application/x-www-form-urlencoded,application/json`

**响应数据类型**:`*/*`

**接口描述**:<p>AI问答</p>

**请求示例**:


```javascript
{
  "empty": true
}
```
**请求参数**:


**请求参数**:


| 参数名称 | 参数说明 | 请求类型    | 是否必须 | 数据类型 | schema |
| -------- | -------- | ----- | -------- | -------- | ------ |
|request||query|true|object||
|jSONObject|JSONObject|body|true|JSONObject|JSONObject|
|&emsp;&emsp;empty|||false|boolean||


**响应状态**:


| 状态码 | 说明 | schema |
| -------- | -------- | ----- | 
|200|OK|SseEmitter|
|400|Bad Request|ResultObject|
|401|Unauthorized|ResultObject|
|403|Forbidden|ResultObject|
|404|Not Found|ResultObject|
|405|Method Not Allowed|ResultObject|
|500|Internal Server Error|ResultObject|


**响应状态码-200**:


**响应参数**:


| 参数名称 | 参数说明 | 类型 | schema |
| -------- | -------- | ----- |----- | 
|timeout||integer(int64)|integer(int64)|


**响应示例**:
```javascript
{
	"timeout": 0
}
```
**响应状态码-400**:

**响应参数**:


| 参数名称 | 参数说明 | 类型 | schema |
| -------- | -------- | ----- |----- | 
|code||integer(int32)|integer(int32)|
|message||string||
|data||object||
|timestamp||integer(int64)|integer(int64)|
|success||boolean||


**响应示例**:
```javascript
{
	"code": 0,
	"message": "",
	"data": {},
	"timestamp": 0,
	"success": true
}
```


**响应状态码-401**:


**响应参数**:


| 参数名称 | 参数说明 | 类型 | schema |
| -------- | -------- | ----- |----- | 
|code||integer(int32)|integer(int32)|
|message||string||
|data||object||
|timestamp||integer(int64)|integer(int64)|
|success||boolean||


**响应示例**:
```javascript
{
	"code": 0,
	"message": "",
	"data": {},
	"timestamp": 0,
	"success": true
}
```


**响应状态码-403**:


**响应参数**:


| 参数名称 | 参数说明 | 类型 | schema |
| -------- | -------- | ----- |----- | 
|code||integer(int32)|integer(int32)|
|message||string||
|data||object||
|timestamp||integer(int64)|integer(int64)|
|success||boolean||


**响应示例**:
```javascript
{
	"code": 0,
	"message": "",
	"data": {},
	"timestamp": 0,
	"success": true
}
```


**响应状态码-404**:


**响应参数**:


| 参数名称 | 参数说明 | 类型 | schema |
| -------- | -------- | ----- |----- | 
|code||integer(int32)|integer(int32)|
|message||string||
|data||object||
|timestamp||integer(int64)|integer(int64)|
|success||boolean||


**响应示例**:
```javascript
{
	"code": 0,
	"message": "",
	"data": {},
	"timestamp": 0,
	"success": true
}
```


**响应状态码-405**:


**响应参数**:


| 参数名称 | 参数说明 | 类型 | schema |
| -------- | -------- | ----- |----- | 
|code||integer(int32)|integer(int32)|
|message||string||
|data||object||
|timestamp||integer(int64)|integer(int64)|
|success||boolean||


**响应示例**:
```javascript
{
	"code": 0,
	"message": "",
	"data": {},
	"timestamp": 0,
	"success": true
}
```


**响应状态码-500**:


**响应参数**:


| 参数名称 | 参数说明 | 类型 | schema |
| -------- | -------- | ----- |----- | 
|code||integer(int32)|integer(int32)|
|message||string||
|data||object||
|timestamp||integer(int64)|integer(int64)|
|success||boolean||


**响应示例**:
```javascript
{
	"code": 0,
	"message": "",
	"data": {},
	"timestamp": 0,
	"success": true
}
```