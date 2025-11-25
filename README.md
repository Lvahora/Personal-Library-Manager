# Personal-Library-Manager


WPF-приложение для управления личной библиотекой. 
Реализовано по junior-требованиям: MVVM, Entity Framework Core + SQLite, валидация, фильтрация, поиск и unit-тесты.

## Требования

- .NET 8 (или .NET 6/7 — в зависимости от твоего проекта)
- Visual Studio 2022
- NuGet-пакеты:
  - `CommunityToolkit.Mvvm`
  - `Microsoft.EntityFrameworkCore.Sqlite`
  - `Microsoft.EntityFrameworkCore.InMemory`

## Запуск

1. Открой решение `PersonalLibraryManager.Wpf.sln` в Visual Studio.
2. Восстанови NuGet-пакеты.
3. Нажми Ctrl+F5 или выбери Отладка → Запуск без отладки.

> При первом запуске создаётся файл `library.db` в папке `bin/Debug/...`.

## Unit-тесты

Проект включает тесты на:
- Репозиторий (`BookRepository`)
- Валидатор (`BookValidator`)
- ViewModel (`MainViewModel`, `AddEditBookViewModel`)
Запуск:
- В Visual Studio: Test → Run All Tests
- Правой кнопкой мыши по проекту PersonalLibraryManager.Tests → Выполнить тесты
