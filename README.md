# StartUp
1) Идея проекта
2) Каскадная модель разработки программы (Проектирование архитектуры -> Дизайн -> Написание кода -> Тестирование -> Поддержка)
3) Идеи для раскрутки проекта (Знакомые , видео-отчет в "tik-tok" , написание статей)
4) Платформа (Андроид)
5) Стэк технологий , который мы будем использовать (kotlin)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Почему именно kotlin:
  - Компания Google , владелец PlayMarKet , магазин приложений для Android , объявил , что kotlin является официальным языком разработки для плафтормы Android
  - Удобная IDE - Android studio , разработана JetBrains специально для разработки приложений на Kotlin под андроид 
  - Встраивыемый java-код , все методы , классы и библиотеки java будут работать в проекте с kotlin
  - Цитата ведущего разработчика Android-проектов "Kotlin же развивается более-менее предсказуемо и предоставляет обертки, которые позволяют использовать все  современные возможности языка, добавляет ряд удобств и возможностей именно для разработки под Android. Это немаловажный фактор, который влияет на удовлетворенность разработчиков."
  - Kotlin — это кроссплатформенный язык программирования со статической типизацией и выводом типов. Kotlin был создан, чтобы решить проблему многословности Java. Этот язык очень хорошо сочетается с различными пакетами SDK для Java и полностью совместим с Java.
Система сборки Android: Android Studio использует Gradle для компиляции ваших приложений. Gradle — это набор инструментов, который автоматизирует процесс сборки с вашими настройками. Gradle упакует ваши ресурсы в пакет приложений Android (APK), который вы можете протестировать, развернуть и выпустить.
XML: Extensible Markup Language, XML, используется для создания файлов макета в приложениях Android. Он похож на HTML, но более строг. Обычно мы называем наши XML-файлы в соответствии с названием нашей деятельности в наших файлах Kotlin или Java. XML также используется в manifest.xmlфайле для определения компонентов. Думайте о XML как о скелете нашего пользовательского интерфейса.
  6) Будем ли мы использовать паттерны проектирования ?
  7) Разобраться с графикой для проекта
  8) Проектирование Базы Данных (PostgreSQL)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Полезная информация для разработки проекта:
  1) https://habr.com/ru/post/341602/ - серия статей на habr , где показывается какое окружение kotlin примерно будет использоваться для разрабокти приложения
  2) https://www.youtube.com/watch?v=30tchn0TjaM - "Котлин за час" хороший видос с примерами и объяснением синтаксиса , циклов , написания функций и других структур
  3) https://www.youtube.com/watch?v=vC1VQUQILlU&list=PLwDTFujB9kIY3daXRyEkfAfdSEYfYfYCR&index=32 - плейлист , где чувак показывает , как он пишет игру на kotlin за 30 серий , одна серия 10-15 минут.
  4) https://martalex.gitbooks.io/gameprogrammingpatterns/content/chapter-2/2.1-command.html - онлайн-книга про паттерны разработки , которые нужны для разрабокти игр
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
1) Обсуждеине код-стиля написания проекта 
2) Примерные сроки выполнения этапов каскадной моедли
3) Использование GitHub , как платформу для обмена версиями проекта

Типовая современная архитектура информационной системы: устройство -> представление -> безнес-логика -> хранение
