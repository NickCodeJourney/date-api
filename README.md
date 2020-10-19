# 日期服务api RESTful APIs


**简介**:日期服务api RESTful APIs


**HOST**:34.92.83.83:8011



# date-controller


## 取N个工作日前-后日期


**接口地址**:`/lifeWorkdayAfterDays/{date}/{nDay}`


**请求方式**:`GET`


**接口描述**:<p>获取指定日期 工作日+N天后或-N天后的实际日期(workday同时支持正数/负数)</p>


**请求参数**:


| 参数名称 | 参数说明       | in   | 是否必须 | 数据类型       | schema |
| -------- | -------------- | ---- | -------- | -------------- | ------ |
| date     | 开始计算的日期 | path | true     | string         |        |
| nDay     | n天            | path | true     | integer(int32) |        |
