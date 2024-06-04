# Додаток для оренди кемперів

**Camper Rental Services**

[Github](https://github.com/PetroBrodetskyi/campers)

[Live page](https://petrobrodetskyi.github.io/campers)

## Огляд

Цей проєкт є тестовим завданням для створення веб-додатка для компанії, яка
пропонує оренду кемперів в Україні.

## Додаток складається з трьох основних сторінок:

### Головна сторінка:

Загальний опис послуг, які надає компанія.

### Сторінка каталогу:

Каталог кемперів з різною комплектацією, місцем знаходження, обладнанням та
типом.

### Сторінка улюблених:

Список оголошень, які користувач додав до улюблених.

## Функціонал

-   Головна сторінка: Загальний опис послуг компанії.
-   Сторінка каталогу: Відображає список оголошень про кемпери. Спочатку
    відображається 4 оголошення, більше завантажуються при натисканні на кнопку
    "Load more". Натискання на кнопку у вигляді серця на оголошенні додає його
    до списку улюблених і змінює колір кнопки. Стан кнопки у вигляді серця
    зберігається при перезавантаженні сторінки. Повторне натискання на кнопку у
    вигляді серця видаляє оголошення зі списку улюблених і повертає колір кнопки
    до початкового стану. Натискання на кнопку "Show more" відкриває модальне
    вікно з детальною інформацією про кемпер. Модальне вікно закривається при
    натисканні на кнопку закриття, натисканні на backdrop або натисканні клавіші
    Esc. Модальне вікно містить деталі про кемпер і відгуки користувачів, які
    відображаються залежно від активної вкладки. Модальне вікно також містить
    форму для бронювання кемпера, яка складається з полів name, email, booking
    date і comment. Поля name, email, booking date є обов'язковими і проходять
    валідацію.
-   Сторінка улюблених: Відображає оголошення, додані користувачем до улюблених.

## Реалізовані технічні вимоги

-   Фіксована верстка в пікселях, семантична та валідна HTML.
-   Відсутність помилок в консолі браузера.
-   Використання Redux для керування станом.
-   Використання Axios для HTTP-запитів.
-   Реалізація на нативному JavaScript з використанням бандлера Vite та React.
-   Інтерактивні елементи працюють відповідно до технічного завдання.
-   Код відформатований та без коментарів.
-   Проєкт задеплойований на GitHub Pages.

## Налаштування бекенду MockAPI

Використаний MockAPI для створення персонального бекенду для розробки.

Створений ресурс з назвою adverts з наступними полями:

\_id name price rating location adults children engine transmission form length
width height tank consumption description details gallery reviews

У базі знаходиться 13 оголошеннь з різними значеннями.

Реалізована пагінація з відображенням 4 оголошень на сторінці.

## Маршрутизація

Використаний React Router для маршрутизації. Визначені наступні маршрути:

-   / - Головна сторінка
-   /catalog - Сторінка каталогу
-   /favorites - Сторінка улюблених

Виконується перенаправлення на головну сторінку для неіснуючих маршрутів.

## Розробка та деплоймент

Додаток розроблений за допомогою React з бандлером Vite. Проєкт задеплоєний на
GitHub Pages.

### Запуск проєкту

1. Клонуйте репозиторій.
2. Встановіть залежності: npm install
3. Запустіть сервер розробки: npm run dev або npm start
4. Відкрийте браузер і перейдіть за адресою http://localhost:3000
