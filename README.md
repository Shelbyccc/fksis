# fksis
# **Требования к проекту**

## **1 Введение**

Название проекта: **Портал факультета КСиС**.   

## **2 Требования пользователя**

### **2.1 Программные интерфейсы**

* Проект разрабатывается на базе фреймворка Laravel 5. Версия PHP от 7 и выше.
* MySQL для хранения информации.

### **2.2 Интерфейс пользователя**

![Alt text](images/main.png "Главный экран")

### **2.3 Характеристики пользователей**

Данное приложение рассчитано на широкий круг пользователей и не имеет возрастного ограничения.    
Минимальные необходимые навыки - умение пользоваться персональным компьютером на базовом уровне и опыт работы с программными продуктами.

## **3 Требования**

## **3.1 Функциональные требования**

Должны быть реализованы следующие страницы/интерфейсы:

* общедоступная главная страница (интерфейс просмотра новостей факультета);
* форма регистрации;
* форма логина;
* форма восстановления пароля;
* страница отдельного пользователя;
* интерфейс управления пользователями (грид с пользователями с возможностью фильтрации и сортировки);
* форма редактирования пользователя;
* страница отдельной новости;
* интерфейс управления новостями(грид с новостями с возможностью фильтрации и сортировки);
* форма редактирования новостей;
* интерфейс управления категориями;
* страница отдельной категории;
* форма редактирования категории;

Атрибутами новостей являются id, название, описание, дата создания, дата последнего обновления, изображение;
Атрибутами категорий являются id, название, описание;
Атрибутами пользователя являются id, полное имя, e-mail, пароль, изображение;

В системе присутствует 4 вида пользователей:
-гости (доступ главной странице, категориям, форме логина и регистрации)
-пользователи (доступ к личному кабинету)
-модераторы (дополнительно доступ к интерфейсам управления новостями и категориями)
-администраторы (дополнительно доступ к интерфейсу управления пользователями) 

## **3.2 Нефункциональные требования**

* Реализация заказа справок, ведомостичек, смены пароля и просмотра расписания для авторизированных пользователей.
