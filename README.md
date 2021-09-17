## Task 3. Momentum для [RS School](https://rs.school/)

![screenshot](images/momentum.png)

[Result](https://fantazer21.github.io/momentum/)

Momentum - аналог [одноимённого приложения](https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca?hl=ru) интернет-магазина Chrome. Приложение показывает время и имя пользователя, его цель на текущий день. Фоновое изображение меняется в зависимости от времени суток. Для хранения данных приложение использует локальное хранилище - local storage.

* Базовая функциональность: воспроизводится функциональность исходного проекта: отображается время; можно ввести имя пользователя и его цель, эти данные сохраняются в local storage и отображаются после обновления страницы, фоновое изображение и приветствие изменяются в зависимости от времени суток. Отличия от исходного проекта: 1) выводится не только время, но и день недели, дата, месяц, например: "Пятница, 25 сентября"; 2) время выводится в 24-часовом формате 3) при клике в поле ввода текст, который там был, исчезает, если пользователь ничего не ввёл или ввёл пустую строку, текст восстанавливается 4) четыре времени суток: утро 6:00-12:00, день 12:00-18:00, вечер 18:00-24:00, ночь 24:00-6:00.
* Смена фонового изображения: Фоновые изображения меняются каждый час, их содержание соответствует времени суток (утро, день, вечер, ночь). Есть кнопка, при клике по которой можно пролистать все фоновые изображения за сутки. Изображения пролистываются в том же порядке, в котором они менялись бы в реальном времени. Основное требование - плавная смена фоновых изображений. Пример плавной смены фонового изображения есть в материалах к заданию. 
* Цитата дня:при загрузке приложения выводится цитата или другой короткий текст (высказывание, шутка, анекдот и т.д.). При перезагрузке страницы или клике на предназначенную для этого кнопку цитата заменяется на другую. Источником цитаты может быть подходящее бесплатное API (предпочтительный вариант) или собственный файл с данными. Язык цитаты русский или английский, на ваше усмотрение. Пример получения цитаты есть в материалах к заданию.
* Прогноз погоды: В приложении выводится прогноз погоды для указанного пользователем города. Прогноз погоды включает в себя иконку погоды, данные о температуре, относительной влажности воздуха, скорости ветра. Пример получения прогноза погоды с объяснением кода есть в материалах к заданию.
* Адаптивный дизайн:приложение корректно отображается как на компьютере, так и на мобильных устройствах. 
([описание задания](https://github.com/rolling-scopes-school/tasks/edit/master/tasks/ready-projects/momentum.md))
