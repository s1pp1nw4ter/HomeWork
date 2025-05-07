# Домашнее задание: Работа с Git, Pull Request, Linter и CI

##  Задание 1: Pull Request

- Создан репозиторий: [https://github.com/s1pp1nw4ter/pull-request.git]
- Создана ветка `pull-request-task`
- Добавлены файлы `main.py` и `config.py`
- Создан pull request: [https://github.com/s1pp1nw4ter/pull-request/pull/1]

##  Задание 2: Разрешение конфликтов + линтинг

- Форкнут репозиторий с конфликтом: [https://github.com/s1pp1nw4ter/fastapi-backend-course.git]
- Конфликт разрешён вручную (удален лишний заголовок функции после merge)
- Выполнена проверка `ruff`: 
  ruff check git/src --fix
  исправил ошибки через nano main.py, с которыми ruff не справился
## Задание 3: Простой CI

- Был создан файл .github/workflows/lint.yml в репозитории.
- В файл добавлен код для настройки CI:
- Как работает CI:

  Этот workflow запускается на каждый push и pull request, если изменяются .py файлы.

  CI-процесс включает:

  Установку Python.

  Установку ruff.

  Запуск линтинга кода через команду ruff check

  Результаты работы CI:

  CI успешно запустился при push и проверил все Python файлы на наличие ошибок.

  Ссылка на запуск CI без ошибок: [https://github.com/s1pp1nw4ter/HomeWork/actions/runs/14879563568]
  Ссылка на запуск CI с найденными ошибками: [https://github.com/s1pp1nw4ter/HomeWork/actions/runs/14879591334]
# HomeWork
