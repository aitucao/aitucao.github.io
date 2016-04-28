接口示例
###pc端房间号获取接口
- 接口名称：www.aitucao.com/getRoomId
- 接口参数信息：无
- 接口返回信息：

	{
	"status":200,
	"msg":"成功",
	"data":{
	"roomId":1234
	}

	或者

	{
	"status":500,
	"msg":"房间号获取失败，房间数已达上限",
	"data":{
	"roomId":0
	}

