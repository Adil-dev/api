# Импорт кандидата из вашей системы в HRMessenger

`POST /v1/projects/{project_id}/import` импортирует кандидата в проект с ID `{project_id}`

Принимаемые параметры:


Имя | Обязательный | Тип | Описание
--- | --- | --- | ---
responseId | да | string | идентификатор отклика или кандидата в вашей системе
name | да | string | Имя кандидата/отклика
phone | да | string | Номер телефона кандидата/отклика
lastname | нет | string | Фамилия кандидата/отклика
info | нет | object | массив или объект с дополнительными данными


Ответ на запрос

```
{
	"status": "success",
	"code": 200,
	"message": "OK",
	"data": true
}
```