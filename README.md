[![Build status](https://ci.appveyor.com/api/projects/status/a9s5ohr1f0n6aff5?svg=true)](https://ci.appveyor.com/project/Ekaterina5885/dz-2-1-selenide)

## Домашнее задание к занятию «2.1. Тестирование веб-интерфейсов»

### Задача - Заказ карты

---

Вам необходимо автоматизировать тестирование формы заказа карты:

<img width="513" alt="order" src="https://user-images.githubusercontent.com/82658524/175577822-f30da4f8-e541-4d38-a33a-b7d3343af05b.png">

Требования к содержимому полей:

1. Поле Фамилия и имя - разрешены только русские буквы, дефисы и пробелы.
2. Поле телефон - только цифры (11 цифр), символ + (на первом месте).
3. Флажок согласия должен быть выставлен.

Тестируемая функциональность: отправка формы.

Условия: если все поля заполнены корректно, то вы получаете сообщение об успешно отправленной заявке:

![success](https://user-images.githubusercontent.com/82658524/175579335-f23bfcbf-5d60-4aa9-91fe-89a3b8c366e3.jpg)

Вам необходимо самостоятельно изучить элементы на странице, чтобы подобрать правильные селекторы.

Проект с авто-тестами должен быть выполнен на базе Gradle, с использованием Selenide/Selenium (по выбору студента).

Для запуска тестируемого приложения скачайте jar-файл из текущего каталога и запускайте его командой: ```java -jar app-order.jar```

Приложение будет запущено на порту ```9999```.

Убедиться, что приложение работает, вы можете открыв в браузере страницу: http://localhost:9999