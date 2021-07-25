# sib-diploma-Track-Penetration-Testing

Дипломная работа к профессии Специалист по Информационной безопасности (Penetration Testing)

## Описание

### Задача

Необходимо протестировать сервис на безопасность - провести полноценое тестирование на проникновение методом черного ящика. О тестируемом приложении известен только адрес.

### Исходные данные
 
1. Требования к тестированию
2. Требования к отчету

## Этапы тестирования


### Этап 1. OSINT

Критерии достижения:

1. Собрано необходимое количество информации о сервисе, были использованы различные сервисы для получения инфомрации - google, shodan, cve-details
1. Собранная информация систематизирована, имеет прямое отношение к тестируемому сервису, имеет ценность для тестирвоания. 
1. Полученная информация оценена и проанализирована

### Этап 2. Scanning

Критерии достижения:

1. Исследумое приложение просканировано прогарммными средствами, такими как NMap (ZenMap), XSpider, Nessus, Accunetix. Для сканирования использованы кастомные настройки, улучшающие эффективность сканирования.
1. При сканировании, так же были сканы на наличие уязвимостей в найденных сервисах, найденные уязвимости провалидированы и проврены на False Positive срабатывания


### Этап 3. Testing

Критерии достижения:

1. Приложение протестировано различными способами, как ручными, так и автоматизированными. 
1. Найденные уязвимости провалидированы и оценены по одной из методик оценки критичности
1. Предложены варианты исправления или рекомендации по быстрому закрытию уязвимости


### Этап 4. Создание отчета

Критерии достижения:

1. Отчет содержит всю необходимую информацию о тестировании, имеет четкую структуру и имеет читабельный вид
1. К каждой уязвимости приложены proof-of-concept и скриншоты подтверждающие успешность атаки
1. Отчет содержит рекомендации по исправлению, а также аналитические рассуждения тестировщика

## Полезные материалы

1. OWASP WSTG
1. HABR - Pentest from 0
1. OWASP Cheat Sheets

### Как правильно задавать вопросы дипломному руководителю?

**Что следует делать, чтобы все получилось:**

* Попробовать найти ответ сначала самому в интернете. Ведь, именно это скилл поиска ответов пригодится тебе на первой работе. И только после этого спрашивать дипломного руководителя
* В одном вопросе должна быть заложена одна проблема 
* По возможности, прикреплять к вопросу скриншоты и стрелочкой показывать где не получается. Программу для этого можно скачать здесь https://app.prntscr.com/ru/
* По возможности, задавать вопросы в комментариях к коду. 
* Начинать работу над дипломом как можно раньше! Чтобы было больше времени на правки. 
* Делать диплом по-частям, а не все сразу. Иначе, есть шанс, что нужно будет все переделывать :)  

**Что следует делать, чтобы ничего не получилось:**

* Писать вопросы вида “Ничего не работает. Не запускается. Всё сломалось.”
* Откладывать диплом на потом. 
* Ждать ответ на свой вопрос моментально. Дипломные руководители - работающие разработчики, которые занимаются, кроме преподавания, своими проектами. Их время ограничено, поэтому постарайтесь задавать правильные вопросы, чтобы получать быстрые ответы! 