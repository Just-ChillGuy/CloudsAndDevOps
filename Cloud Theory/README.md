# Бобров Иван K3221

# Задание №1

## Вариант 7. Опишите бессерверные вычисления. Как это так, вычисления без сервера?

Думаю, удобнее всего будет просто взять формулировку с какого-нибудь сайта, а далее расшифровать её. Итак, что же это такое: это метод предоставления серверных услуг без использования физического оборудования, то есть, без его покупки или аренды. Суть бессерверных вычислений заключается в том, что клиент получает готовое решение без необходимости его настройки, обслуживания и т.д.. Также используются ровно столько ресурсов, сколько требуется, то есть недостатка или избытка мощности не существует, а это экономия финансовых ресурсов, ведь в первом случае возможны какие-либо издержки, а во втором - банальная переплата. Физически все серверы существуют, постоянно обновляются и обслуживаются, но только выполняет все процедуры облачный провайдер. Теперь стоит разобрать их преимущества и недостатки.

## + :

1) Безопасность - за это отвечает поставщик услуг, который, вероятно, будет соблюдать лучше стандарты безопасности. Если утечка данных всё же произойдёт и будет доказано, что виноват провайдер, то можно запросить у него компенсацию, а не будь его, то данную проблему пришлось бы решать самим.

2) Снижение расходов - т.к. используется только мощность, которой достаточно для удовлетворения потребностей компании, не будет её избытка, из-за которой прогорят финансовые ресурсы. Например, существуют моменты, когда сервера находятся в простое, в обычном случае они бы продолжали работать в стандартном режиме, в то время как при бессерверных вычислениях их мощность снизится. Более того, количество выделяемых ресурсов динамическое, т.е. изменяется в зависимости от нагрузки. Также не требуются специалисты для поддержания работоспособности серверов, не нужно тратить время на их развёртывание, что тоже положительно скажется на финансах.

3) Высокая отказоустойчивость - провайдер обеспечивает постоянный доступ в систему

4) Различные интеграции - на сегодняшний день компании всё больше и больше используют облачные технологии, благодаря бессерверным вычиселниям процесс интеграции с другими сервисами упрощается, плюсы этого очевидны.

## - :

1) Холодный старт - если долго не использовалась функция, то её запуск будет относительно долгим.

2) Отсутствие аозможности насторойки - т.к. серверами занимается провайдер, мы не можем их настроить под себя.

3) Трудоёмкие запросы резко повышают стоимость услуги - на длительная или ресурсозатратная задачу придётся сильно вложиться, поэтому на мой взгляд для начала нужно рассчитать, что будет дешевле - использовать бессерверные вычисления или разместить у себя сервер/серверы 

Типичные представители поставщиков данной услуги:

AWS Lambda (лимит времени выполнения: до 15 минут), Azure Functions(лимит времени выполнения: до 10 минут, в платной версии это значение увеличивается), Google Cloud Functions (Лимит времени выполнения: до 9 минут), IBM Cloud Functions, Cloudflare Workers (ограничение по времени выполнения - менее 50 мс в бесплатной версии)

# Задание №2

## Вариант 7. Поговорим про безопасность. Какие существуют направления повышения безопасности в облаке? Какие компоненты безопасности настраивать обязательно? 

1) Необходимо давать только те права доступа сотрудникам, которые им действительно нужны, то есть не давать повышенных прав, иначе информация может утечь/произойдёт саботаж из-за возможной их неблагонадёжности (конечно, не все сотрудники импостеры, но такое периодически случается).

2) Шифруем данные - если их как-то получат, то их считывание будет затруднительно.

3) Проверяем логи - вовремя наёденная подозрительная активность предотвратит катастрофу.

4) Использование безопасного соединение, виртуальных сетей - такое трудно будет перехватить, ведь злоумышленник просто не будет иметь к ним доступа

5) **Установка свежего ПО** - к этому вопросу надо подходить ответственно, не всегда новая версия лучше старой. В теории это устраняет новые и старые уязвимости, но лучше сначала подумать, стоит ли устанавливать. В любом случае сидеть на старом ПО неправильно, нужно искать более новые и стабильные версии с исправленными уязвимостями.

6) Использование секретохранилок - надёжный способ хранения паролей и т.д., легко настраивать доступ к ним в отдельных случаях

7) Использование сервисов от Дудос атак - никто не хочет, чтобы их сервер упал, это всегда убытки и минус социальный рейтинг

8) Повышение осведомлённости сотрудников о кибер и не только опасностях - бывают случаи, когда сотрудник может скачать из письма вирус и т.д., последствия известны.

9) Резервное копирование - потеря данных может стоить нам кучу денег и нервов.

Если говорить про обязательную настройку, то у хорошего сервиса должно быть всё сделано из вышеперечисленного, потому что тогда при желании брешь в системе найти будет легко, да и сами мои предложения не являются чем-то экстраординарным,  любой мошенник про это знает, а значит в первую очередь будет через них пробиться.  

