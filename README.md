# Pet-проект: Веб-приложение для управления задачами (Task Manager)
## Описание:
Создание веб-приложения, которое позволяет пользователям создавать, управлять и отслеживать свои задачи.
## Функциональность:
* Регистрация и аутентификация пользователя:
  * Пользователи могут создать учетную запись и войти в систему.
  * Хранение данных пользователей в базе данных.
* Управление задачами:
  * Создание, просмотр, редактирование и удаление задач.
  * Каждая задача должна иметь название, описание, срок выполнения и статус (выполнена/не выполнена).
* Фильтрация и сортировка задач:
  * Возможность фильтровать задачи по статусу (выполненные/не выполненные) и сортировать их по дате создания или сроку выполнения.
* Уведомления:
  * Оповещение пользователя о приближающемся сроке выполнения задачи.

## Стек технологий:
* Java 
* Spring Framework (Spring Boot, Spring MVC)
* PostgreSQL (для хранения пользовательских данных и задач)
* HTML, CSS, JavaScript (для создания пользовательского интерфейса)
* Thymeleaf
* Spring Security
* Gradle
* JavaMail API для отправки электронных уведомлений