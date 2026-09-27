# Домашнее задание: Рефакторинг в ООП-стиле

**Максимальный балл: 100**

## Цель
Научиться проектировать гибкую архитектуру Java-приложения с использованием принципов ООП (инкапсуляция, полиморфизм).

## Задача
Создать приложение, которое:
1. Читает `.class` файл и разбирает его структуру
2. Выполняет две проверки:
   - **Идиоматичность имен методов** (camelCase)
   - **Количество полей** (не более 10)
3. Выводит результаты в консоль
4. Спроектиравно с учетом возможности:
   - добавления проверок 
   - добавления возможности настройки формата вывода

"Спроектиравно с учетом возможности" означает, что при добавлении указанной возможности нужно будет
просто реализовать ее и для ее подключения нужно будет поменять условно 2-3 строки в оригинальном коде.

## Этап 1: Прототип
- Написать "грязный" прототип (можно с ИИ)
- Принимает путь к `.class` файлу как аргумент
- Выполняет обе проверки
- Выводит результат: PASS/FAIL + причина

## Этап 2: Рефакторинг в ООП

## Сдача
- pull request 

## Полезные ссылки

### ООП и SOLID
- [SOLID — Википедия](https://ru.wikipedia.org/wiki/SOLID_(%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5))
- [Принципы SOLID в Java — Baeldung](https://www.baeldung.com/solid-principles)
- [SOLID на русском с примерами — Habr](https://habr.com/ru/articles/687802/)

### Паттерны проектирования (GoF)
- [Паттерны GoF — Википедия](https://ru.wikipedia.org/wiki/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
- [Refactoring Guru — Паттерны (русский)](https://refactoring.guru/ru/design-patterns)
- [Java Design Patterns — GitHub](https://github.com/iluwatar/java-design-patterns)

### Принципы проектирования
- [Separation of Concerns — Википедия](https://ru.wikipedia.org/wiki/%D0%A0%D0%B0%D0%B7%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D0%BE%D1%82%D0%B2%D0%B5%D1%82%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D1%81%D1%82%D0%B8)
- [DRY, KISS, YAGNI — Habr](https://habr.com/ru/articles/144683/)
- [Принципы проектирования — Baeldung](https://www.baeldung.com/design-principles)

### Спецификация JVM и class-файлы
- [JVM Spec, Chapter 4 — Oracle](https://docs.oracle.com/javase/specs/jvms/se26/html/jvms-4.html)
- [Class File Format — Oracle](https://docs.oracle.com/javase/specs/jvms/se26/html/jvms-4.html)

### Рефакторинг
- [Каталог рефакторингов — Refactoring Guru](https://refactoring.guru/ru/refactoring)
- [Рефакторинг. Улучшение существующего кода — Мартин Фаулер](https://martinfowler.com/books/refactoring.html)

### Дополнительно
- [Java Code Conventions — Oracle](https://www.oracle.com/java/technologies/javase/codeconventions-contents.html)
- [Effective Java — Джошуа Блох](https://www.oreilly.com/library/view/effective-java-3rd/9780134686097/)
