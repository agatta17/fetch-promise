# Пример работы с Fetch и Promise
__[Демо](https://agatta17.github.io/fetch-promise/?username=agatta17)__

## Создание запросов. Fetch
1. Выполняется запрос для получения информации о пользователе на github.com. Ник пользователя задается в параметре URL. Если ник в параметре не задан, то для запроса используется мой ник.
2. Выводится аватарка, имя (или логин, если имя не задано), описание профиля и ссылка на страницу пользователя.
3. Если получить информацию о пользователе не получилось, выводится соответствующее сообщение.

## Работа с асинхронностью. Promise
1. SetTimeout, функция которого возвращает new Date, обернут в promise. Чтобы можно было продолжить вычисление, после пройденного времени.
2. После того как пройдет время таймера и завершится запрос, выводится информация о пользователе и текущая дата. 
3. Пока мы не получили всю необходимую информацию, показывается прелоадер.
