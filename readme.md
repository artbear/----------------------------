# Свой собственный обработчик деталек, настроек приложения из ОСени в коде самого приложения

позволяет переопределить каталог проекта в детальках из autumn-properties.json
- заменяется `%КаталогПроекта%` в начале строки-значения
  - например, `"ФайлВКаталогеПроекта" : "%КаталогПроекта%/fixtures/cf"`
- также заменяется `КаталогПроекта`

Вся магия в 2х классах
- `Классы\АннотацияОбработчикДеталек.os`
- `Кл`ассы\РеализацияАннотацииОбработчикДеталек.os`

в классе `Классы\ТестОбработчикаДеталек.os` выполняется тест

запускать скрипт через `oscript main.os`
