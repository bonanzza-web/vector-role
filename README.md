# Роль установки Vector

Эта роль предназначена для автоматизированной установки и настройки Vector - мощного инструмента сбора, обработки и отправки логов. Вам больше не нужно заниматься рутинными процедурами настройки и установки, благодаря этой роли.

# Основные задачи роли:

   1. Установка Vector: Роль позволяет легко установить нужную версию Vector с официальных репозиториев.
   2. Настройка конфигурации: Роль позволяет настроить конфигурационный файл Vector с помощью переменных, что делает процесс настройки гораздо более гибким и управляемым.
   3. Запуск и управление: Роль автоматически запускает Vector после установки и предоставляет возможность управления им как службой.

# Переменные роли:

    vector_version: Версия Vector для установки.
    vector_config: Конфигурация Vector в формате YAML. Здесь можно указать источники, преобразования, приемники и другие настройки.
    
# Зависимости:

Для корректной работы роли требуется предварительно установленный Vector и настроенный ClickHouse.

С этой ролью вы сможете значительно упростить и автоматизировать установку и настройку Vector, что сэкономит ваше время и снизит вероятность ошибок.
