#  Задание:

Вам необходимо создать Spring Boot приложение, которое управляет доступом к ресурсам в зависимости
от роли пользователя. У вас должно быть два типа пользователей: USER и ADMIN.

* Создайте ресурс /private-data, доступный только для аутентифицированных пользователей с ролью ADMIN
* Создайте ресурс /public-data, доступный для всех аутентифицированных пользователей независимо от их роли
* Реализуйте форму входа для аутентификации пользователей с использованием стандартных средств Spring Security
* Если неаутентифицированный пользователь пытается получить доступ к /private-data, он должен быть перенаправлен на форму входа