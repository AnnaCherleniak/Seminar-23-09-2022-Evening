# Инструкция по работе с Git

## Создание репозитория
Для создания репозитория используется команда *git init*. Для того, чтобы создать репозиторий, отройте в терминале пустую папку и в нём напишите *git init*

## Добавление файла к коммиту
Для добавления файла к новому коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием выполните команду *git add <название файла>*.

## Создание коммитов
Для того, чтобы выполнить коммит, используется команда *git commit*. Для этого в терминале с папкой-репозиторием напишите команду *git commit -m <сообщение к коммиту>*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***. Все файлы коммит должны быть предворительно добавлены.

## Определение состояния
Команда *git status* показывает информацию о текущем состоянии папки-репозитория: актуальна ли информация в ней и состоянии папки.

## Как посмотреть все коммиты
Чтобы открыть журнал всех изменений, используется команда *git log*. В терменале появится список всех проведенных коммитов.

## Отслеживание изменений
Чтобы увидеть, какие есть изменения, и сравнить сохраненную и еще не сохраненную версии, ипользуется команда *git diff*.