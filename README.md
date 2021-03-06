# 📝 | Финансовый Помощник (Financial Assistant)

## Цель разработки

Главной целью является предоставление возможности сведения информации по стандаратным финансовым инструментам в одну систему для пользовательского контроля за состоянием общего баланса и за его изменениями. Система должна предоставлять возможность добавления, редактирования и удаления данных по счету пользователя и по пополнениям / расходам.

## Платформа, инструменты, средства

В качестве ключевых инструментов для разрабатываемого приложения были выбраны:

- **Целевая платформа**: мобильное приложение на базе *iOS 13+*;
- **Библиотека для построения приложения**: *[Flutter](https://flutter.dev)* с использованием языка *[Dart](https://dart.dev)*;
- **Хранение данных**: локально на устройстве с помощью *[Shared Preferences](https://pub.dev/packages/shared_preferences)*.

## Описание приложения 

В мобильное приложение заложено наличие 5 экранов:

1. **Summary** (сведение о текущем балансе пользователя по всем банковским счетам, информация о транзакциях и о счетах);
2. **Income / Outcome** (список пополений и расходов по всем счетам);
3. **Edit Income / Outcome** (редактирование пополнений и расходов);
4. **Account** (экран счета со списком транзакций по нему);
5. **Edit Account** (редактирование счета).

## Цветовая палитра

- ![#FFFFFF](https://placehold.it/15/FFFFFF/000000?text=+) `#FFFFFF` — фон для выделенных компонентов (белый);
- ![#F4FAFF](https://placehold.it/15/F4FAFF/000000?text=+) `#F4FAFF` — фон для основной части приложения;
- ![#568EA3](https://placehold.it/15/568EA3/000000?text=+) `#568EA3` — ссылки и кнопки;
- ![#23395B](https://placehold.it/15/23395B/000000?text=+) `#23395B` — фон для выделенных компонентов (темно-синий);
- ![#19323C](https://placehold.it/15/19323C/000000?text=+) `#19323C` — текст;
- ![#216000](https://placehold.it/15/216000/000000?text=+) `#216000` — "стрелка" для обозначения пополнений;
- ![#AF0000](https://placehold.it/15/AF0000/000000?text=+) `#AF0000` — "стрелка" для обозначения расходов.
