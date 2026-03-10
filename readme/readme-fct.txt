Перепеши файл README.md
(Пиши все на англиском, используй жаргон проффесионаальных програмистов. Пиши все максимально подробно. Пиши все максимально подробно, так же бери информацию из уже созданного README.md. Так же по тексту можешь использовать Markdown Alerts:
> [!NOTE]
> [!TIP]
> [!IMPORTANT]
> [!WARNING]
> [!CAUTION])
1. Заголовок и Описание
Название проекта: Четкое и крупное, бад на мой профиль.
(например: # FCT Blueprint Decoder Encoder <a href="https://github.com/OstinUA"><img align="right" src="https://img.shields.io/badge/OstinUA-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
)
Краткий слоган: Одно предложение, объясняющее суть.
Бэджи (Badges): Статус сборки, версия, лицензия, покрытие тестами и т.д. 
(Например: [![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge)](LICENSE))
2. Оглавление
Полезно, если проект объемный. Позволяет быстро перемещаться по разделам.
3. Особенности (Features)
Подробний список возможностей.
4. Технологический стек
Перечисление основных языков, фреймворков и библиотек (например, Python 3.10, FastAPI, PostgreSQL).
Технический блок
Project Structure, Key design decisions
5. Начало работы (Getting Started)
Разделите на два подпункта:
Требования (Prerequisites): Что должно быть установлено в системе (Node.js, Docker, Python и т.д.).
Установка (Installation): Пошаговые команды для клонирования репозитория и установки зависимостей.
6. Тестирование (Testing)
Инструкции по запуску тестов. Команды для unit-тестов, интеграционных тестов или линтеров (например, pytest, npm run test, flake8).
7. Развертывание (Deployment)
Руководство по деплою. Сборка для продакшена (например, Docker Compose, CI/CD пайплайны, деплой на облачные платформы).
8. Использование (Usage)
Примеры кода или команды для запуска.
Лучше всего оформить это в виде блока кода с комментариями.
9. Конфигурация
Описание переменных окружения (.env), флагов запуска или конфигурационных файлов.
Сообщество и поддержка
10. Лицензия
Укажите тип лицензии (MIT, Apache 2.0 и т.д.), чтобы пользователи знали свои права.
11. 
## Community and Support

Project created with the support of the FCTostin community.

[![YouTube](https://img.shields.io/badge/YouTube-Channel-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@FCT-Ostin)
[![Telegram](https://img.shields.io/badge/Telegram-Join_Chat-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/FCTostin)
[![Steam](https://img.shields.io/badge/Steam-Join_Group-1b2838?style=for-the-badge&logo=steam&logoColor=white)](https://steamcommunity.com/groups/FCTgroup)

## Support the Development

[![Patreon](https://img.shields.io/badge/Patreon-Support-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/c/OstinFCT)
[![Boosty](https://img.shields.io/badge/Boosty-Donate-F15F2C?style=for-the-badge&logo=boosty&logoColor=white)](https://boosty.to/ostinfct)

Так же создай CONTRIBUTING.md который бы подходил под этот репозиторий.
(Пиши все на англиском, используй жаргон профессиональных програмистов.) 
Структура файла CONTRIBUTING.md
1. Введение (Introduction)
Краткое приветствие и благодарность за желание внести свой вклад в проект.
2. Куда задавать вопросы (I Have a Question)
Четкое указание, что баг-трекер (Issues) не предназначен для вопросов по использованию. Направление пользователей в Discussions, Stack Overflow или профильные чаты.
3. Сообщения об ошибках (Reporting Bugs)
Инструкция по созданию качественного баг-репорта.
Поиск дубликатов: Просьба сначала проверить открытые Issues.
Окружение (Environment): Требование указывать версию ОС, версию приложения, версию языка/фреймворка.
Шаги для воспроизведения (Steps to Reproduce): Подробный алгоритм, как вызвать баг.
Ожидаемое и фактическое поведение (Expected vs Actual Behavior).
4. Предложение улучшений (Suggesting Enhancements)
Как правильно предложить новую фичу.
Обоснование необходимости (какую проблему решает).
Примеры использования (Use cases).
5. Локальная разработка (Local Development / Setup)
Пошаговое руководство для запуска проекта на машине контрибьютора.
Как сделать Fork и Clone репозитория.
Установка зависимостей (например, npm install, pip install -r requirements.txt).
Настройка переменных окружения (копирование .env.example в .env).
Запуск локального сервера или сборки.
6. Правила работы с Git и Pull Requests (Pull Request Process)
Самый важный технический раздел.
Стратегия ветвления: Как называть ветки (например, feature/название-фичи, bugfix/номер-ишью).
Оформление коммитов: Требование использовать Conventional Commits (например, feat: add login, fix: resolve crash on startup).
Синхронизация с upstream: Напоминание о необходимости подтягивать изменения из основной ветки перед созданием PR.
Описание PR: Что должно быть в описании (ссылки на Issues, скриншоты для UI-изменений).
7. Стандарты кода (Styleguides)
Требования к качеству и стилю кода.
Используемые линтеры и форматтеры (ESLint, Prettier, Black, Flake8).
Специфичные архитектурные паттерны проекта, если они есть.
8. Тестирование (Testing)
Требование покрывать новый код тестами.
Команды для запуска локальных тестов.
9. Процесс ревью (Code Review Process)
Краткое описание того, кто проверяет код, сколько аппрувов нужно для слияния (merge) и как реагировать на замечания ревьюеров.
