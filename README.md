# Пример работы с Fetch и Promise
__[Посмотреть демо](https://agatta17.github.io/fetch-promise/?username=agatta17)__

## Создание запросов. Fetch
1. Выполняется запрос для получения информации о пользователе на github.com. Ник пользователя задается в параметре URL. Если ник в параметре не задан, то для запроса используется мой ник.
2. Выводится аватарка, имя (или логин, если имя не задано), описание профиля и ссылка на страницу пользователя.
3. Если получить информацию о пользователе не получилось, выводится соответствующее сообщение.

## Работа с асинхронностью. Promise
1. Оберни SetTimeout, функция которого возвращает new Date, в promise. Чтобы можно было продолжить вычисление, после пройденного времени.
2. Используй проект из задания с Fetch. (Получение информации о пользователе) 
3. И выведи информацию после того как пройдет время таймера и завершится запрос. Нужно вывести информацию о пользователе и текущую дату. Для выполнения используй Promise.all().
4. Пока мы не получили всю необходимую информацию показывай прелоадер.
