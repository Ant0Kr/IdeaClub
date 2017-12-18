# Результаты тестирования

## Сценарий 001-01: Зарегистрироваться со вводом верных данных
1. Перейти по ссылке "Register", ввести в форму верные данные, нажать кнопку Register
### Ожидаемый результат: отобразилась страница авторизации, запись о пользователе создалась в базе данных
### Фактический результат: 
### Оценка: 
## Сценарий 001-02: Зарегистрироваться со вводом неверных данных
1. Перейти по ссылке "Register", ввести в форму неверные данные, нажать кнопку Register
### Ожидаемый результат: снова отобразилась сраница регистрации с выводом причины отказа
### Фактический результат: 
### Оценка: 
## Сценарий 002-01: Пройти авторизацию со вводом верных данных
1. Перейти по ссылке "Login", ввести в форму верные данные, нажать кнопку Login
### Ожидаемый результат: 
### Фактический результат: 
### Оценка: 
## Сценарий 002-02: Пройти авторизацию со вводом неверных данных
1. Перейти по ссылке "Login", ввести в форму неверные данные, нажать кнопку Login
### Ожидаемый результат: снова отобразилась сраница авторизации с выводом причины отказа
### Фактический результат: 
### Оценка: 
## Сценарий 002-03: Пройти авторизацию через внешний сервис
1. Перейти по ссылке "Login", нажать кнопку одной из доступных соцсетей
### Ожидаемый результат: отобразилась (или была пропущена, в зависимости от того, была ли при прошлой авторизации поставлена галочка "запомнить") страница авторизации внешнего сервиса, после прохождения авторизации, если такого пользователя не было в базе данных приложения, предлагается ввод email. После завершения авторизации отобразилась главная страцица, в правом верхнем углу отображается имя пользователя, стали доступны пользовательские списки фильмов
### Фактический результат: 
### Оценка: 
## Сценарий 003-01: Выйти из учетной записи
1. Перейти по ссылке "Log out" от имени авторизованного пользователя
### Ожидаемый результат: отобразилась главная страница, пропал доступ к пользовательским спискам и пользовательской оценке, появился доступ к страницам регистрации и авторизации
### Фактический результат: 
### Оценка:
## Сценарий 004-01: Обновление главной фотографии.
1. Нажать на главной странице пользователя кнопку смены фотографии, выбрать фото.
### Ожидаемый результат: на главной странице изменилась фотография.
### Фактический результат: 
### Оценка:
## Сценарий 004-02: Добавление фотографий во вкладке "Photos".
1. Нажать на главной странице на вкладке "Photos" кнопку "Add photo", выбрать фото.
### Ожидаемый результат: во вкладке "Photos" добавилась фотография.
### Фактический результат: 
### Оценка:
## Сценарий 005-01: Добавление поста на вкладке "Activity".
1. На главной странице пользователя зайти на вкладку "Activity", в текстовом поле ввести текст поста и нажать на кнопку "Add".
### Ожидаемый результат: во вкладке "Activity" появился новый пост, в котором корректно отобразилось время добавления, имя и фото пользователя, кто его добавил.
### Фактический результат: 
### Оценка:
## Сценарий 006-01: Добавление комментария на вкладке "Activity".
1.  На главной странице пользователя зайти на вкладку "Activity", в текстовом поле под постом ввести текст поста и нажать на кнопку "Add".
### Ожидаемый результат: во вкладке "Activity" появился новый комментарий под постом, в котором корректно отобразилось время добавления, имя и фото пользователя, кто его добавил.
### Фактический результат: 
### Оценка:007-01: Добавление информации о себе во вкладке "About".
1. Нажать на главной странице на вкладке "About" кнопку "Add", ввести тему и содержимое.
### Ожидаемый результат: во вкладке "About" добавилась новая информация о пользователе, тема выделяется жинрым цветом.
### Фактический результат: 
### Оценка:
## Сценарий 008-01: Переход на страницы других пользователей.
1. Нажать на фотографию или имя другого пользователя.
### Ожидаемый результат: переадресация на страницу пользователя, на ссылку которого вы нажали.
### Фактический результат: 
### Оценка: