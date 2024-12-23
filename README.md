# int7

# Формы для записи данных о хакерских группировках и инцидентах безопасности

Этот проект позволяет записывать данные о хакерских группировках и инцидентах безопасности в файл CSV с использованием веб-интерфейса на базе библиотеки `NiceGUI`.

## Требования

Для работы с проектом вам потребуется:

- Python 3.7 или выше
- Установленные библиотеки:
  - `nicegui`
  - `csv`

Вы можете установить необходимые библиотеки с помощью pip:

```bash
pip install nicegui
```

## Форма для хакерских группировок
### Описание
Эта форма позволяет пользователю ввести информацию о хакерской группировке, включая:

- Дата атаки
- Название группировки
- Ссылка на канал/сообщество
- Язык общения
- Регион атак
- Альтернативные названия
- Связи с другими группировками
- Атакуемые организации
- Методы атаки (с возможностью выбора нескольких вариантов)
- Какой софт и вредоносное ПО использует группировка
- Целевая направленность
- Мотив
 -Регулярность атак
- Уровень угрозы

## Форма для инцидентов безопасности
### Описание
Эта форма позволяет пользователю ввести данные о безопасности инцидента, включая:

- Дата сообщения
- Источник сообщения
- Название организации
- Тип инцидента (например, "Взлом" или "Утечка данных")
- Методы атаки (если тип инцидента — "Взлом")
 -Описание данных (если тип инцидента — "Утечка данных")
- Возможные последствия для организации

## Как запустить проект
1. Клонируйте репозиторий:
```bash   
git clone https://github.com/SL1MP/int7.git
```
2. Перейдите в директорию проекта:
```bash
cd int7/forms
```
3. Установите зависимости:
```bash
pip install nicegui
```
4. Запустите сервер:
```bash
python hackers.py
```
или
```bash
python incident_form.py
```
Формы собирают данные и записывают их в CSV файлы.

### Отчёт
Файл отчёта, Отчёт.md, о анализе инцидентов и хакерских группировок представлен по пути:
```bash
cd int7/otch
```
В данной папке находятся используемые изображения, титульный лист и сам отчёт.

### Отчёт был выполнен в приложении Obsidian, для лучшего восприятия и понимания, просьба открывать отчёт в данном приложении!!! По всем вопросам обращаться в телеграмм - @vldm19, почта - dementev647@gmail.com.
