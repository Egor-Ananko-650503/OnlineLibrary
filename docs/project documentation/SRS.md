# Требования к проекту
## Содержание

## 1. Введение
### 1.1 Назначение
В этом документе описаны функциональные и нефункциональные требования к веб-приложению «OnlineLibrary». Он предназначен для команды, занимающейся сопровождением данного веб-приложения.
### 1.2 Бизнес-требования
В современном мире библиотеки не являются важной частью досуга/учебы/работы каждого человека. Одной из причин этого является то, что в некоторых библиотеках действуют неудобные системы библиотечного, информационного и справочно-библиографического обслуживания пользователей. Отсюда возникает необходимость создания грамотного ресурса для работников и пользователей библиотек. Данное веб-приложение позволяет полностью организовывать рабуту как администратора библиотеки (выдача книг, добавление книг и т. д.), так и пользователя (поиск книг, бронирование книг и т. д.).
### 1.3 Аналоги
Аналогами данного веб-приложения являются в основном веб-сайты библиотек университетов и крупных, известных библиотек (таких как Нациаональная Библиотека Беларуси).
## 2. Требования пользователя
### 2.1 Программные интерфейсы
Приложение реальзовано с использованием технологий Servlets и JSP и библиотеки тегов JSTL. Вся информация хранится в реляционной базе данных.
### 2.2 Интерфейс пользователя
Стартовая страница
Страница регистрации
Гланая страница администратора

### 2.3 Характеристики пользователей
#### 2.3.1 Классы пользователей
1. Клиент - зарегистрированный на сайте пользователь, имеющий возможность бронировать книгу, просматривать список всех книг, осуществлять поиск по каталогу, просматривать свои заявки на бронь и взятые книги.
2. Администратор - зарегистрированный на сайте пользователь, имеющий возможность управления информацией о книгах и пользователях (добавление книги, просмотр новых заявок на бронь, подтверждение или отклонение брони, выдача книги, поиск по книге, вывод списка всех книг и т. д.).
#### 2.3.2 Целевая аудитория
Приложение разработано для всех людей, желающих воспользоваться услугами библиотеки с минимальным затратом на это времени и сил.
## 3. Системные требования
### 3.1 Функциональные требования
#### 3.1.1 Вход пользователя в приложение
Пользователь имеет возможность входа в приложение при вводе своего логина и пароля.
#### 3.1.2 Регистрация пользователя в приложении
Пользователь имеет возможность зарегистрироваться в приложении, указав свои данные: имя, фамилию, адрес электронной почты, логин и пароль.
#### 3.1.3 Выход пользователя из приложения
Пользователь имеет возможность выхода из приложения. После этого действия он будет возвращен на главную страницу приложения.
#### 3.1.4 Просмотр всех книг библиотеки, а также поиск по книге
Пользователь имеет воозможность просмотреть все книги, находящиеся в каталоге, или найти нужную ему книгу, воспользовавшись поиском.
#### 3.1.5 Бронирование книги
Пользователь-клиент имеет возможность забронировать книгу, которую он хочет впоследствии взять в библиотеке. Бронь действительна 4 дня.
#### 3.1.6 Управление информацией о книгах
Пользователь-администратор имеет возможность управлять информацией о книгах, а именно добавлять книгу или изменять информацию о книге.
#### 3.1.7 Управление информацией о заказах пользователей
Пользователь-администратор имеет возможность управлять бронью пользователя (может либо подтвердить, либо отклонить ее) и выдачей пользователю книги.
### 3.2 Нефункциональные требования
#### 3.2.1 Атрибуты качества
##### 3.2.1.1 Требования к удобству использования
1. Фон страниц, а так же фон элементов должен быть светлым. 
2. Шрифт, рамки элемнтов должны быть темными.
3. Все функциональные элементы пользовательского интерфейса имеют названия, описывающие действие, которое произойдет при выборе элемента.
##### 3.2.1.1 Требования к безопасности
1. Каждая бронь или заказ книги должны храниться в бд и содержать в себе уникальный номер брони или заказа, информацию о пользователе и информацию о книге.
2. Пароли пользователей не должны храниться в базе данных в своем первичном виде (должны быть зашифрованы каким-либо алгоритмом).
#### 3.2.2 Внешние интерфейсы
Приложение удобно для использования пользователями с проблемами со зрением, так как веб-страницы являются контрастными (светлый фон, темный шрифт), размер шрифта не менее 12-14 пт., все основные элементы находятся в центре веб-страницы и имеют крупный размер.
#### 3.2.3 Ограничения
1. Приложение реальзовано с использованием технологий Servlets и JSP, использовалась также библиотека тегов JSTL.
2. Вся информация о пользователях, книгах, авторах, бронях и заказах хранится в базе данных.



