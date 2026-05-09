RUS Config Donetsk Website

Загрузи содержимое этой папки на любой статический хостинг.

Файлы, которые должны быть доступны в интернете:
- index.html
- version.json
- RUS_Config_Donetsk_3.1.0.zip
- assets/*

После публикации возьми ссылку на version.json, например:
https://example.com/rus-config/version.json

И пропиши ее на компьютерах в:
D:\RUS Config Donetsk\update-source.json

Формат:
{
  "manifest": "https://example.com/rus-config/version.json"
}

Если version.json и zip лежат рядом, поле package может быть просто:
"package": "RUS_Config_Donetsk_3.1.0.zip"