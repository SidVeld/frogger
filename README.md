# Frogger

## АВТОМАТИЗАЦИЯ ПРОЦЕССА ПОИСКА И ПУБЛИКАЦИИ МЕРОПРИЯТИЙ НА САЙТ УПРАВЛЕНИЯ АКСЕЛЕРАЦИОННЫХ ПРОГРАММ И ПРОЕКТНОГО ОБУЧЕНИЯ ГУУ

В качестве темы проектной работы была выбрана автоматизация процесса обновления ленты мероприятий [Сайта УАПиПО ГУУ](http://pmo.guu.ru/all-events/).

На ней выкладываются актуальные `конкурсы`, `акселерационные` и `инкубационные программы`, `хакатоны`, `кейс-чемпионаты`, `конференции` и `другие` события, с помощью которых обучающиеся могут значительно ускорить разработку и повысить качество собственных проектов. Сейчас обновление ленты мероприятий происходит исключительно в ручном режиме, что занимает много времени у администратора сайта.

**Гипотеза**, на которой строится проект, состоит в том, что существующий процесс обновления ленты мероприятий сайта УАПиПО может быть автоматизирован, а сама автоматизация, с одной стороны, позволит значительно **сократить трудозатраты** вовлеченных сотрудников, а с другой стороны, поможет обеспечить **своевременное появление мероприятий на сайте**, что даст обучающимся больше времени на подготовку.

В рамках работы над проекты были разработаны (AS IS)[https://drive.google.com/file/d/1NnZAt0cczjUkmpYIpka7kPa2cvbftCo9/view?usp=sharing] и (TO BE)[https://drive.google.com/file/d/1K1ChAl1Flo6hVMBam-A16nuf1nykOOqB/view?usp=sharing] модели процесса.

Автоматизировать планируется большую часть существующего процесса. Работа администратора сайта, сейчас выполняющего все вручную, будет сводиться к обработке контента, автоматически собранного в базу данных на предыдущих шагах. Взаимодействие с базой данных будет производиться с помощью специально созданного программного интерфейса в виде плагина для системы управления содержимым WordPress, а также бота для мессенджера Telegram.

Для получение информацию создаются парсеры (их скрипты можно найти в директории frogger). Так же ведется работа над обработкой данных внутри БД (папка sql).