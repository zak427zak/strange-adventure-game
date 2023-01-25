# Игра "Simple Adventure"

Игра представляет собой генераторное помещение (размеры задаете при инициализации), состоящее из комнат. 
Она основана на данном задании + добавлена логика из предыдущего проекта (3.3)

Цель игры проста: добраться из комнаты А в комнату Б (генерируются текущая точка и точка-цель)

- Герой совершает шаги в 4 направлениях, и указывает количество шагов. 
- Если полей меньше, чем шагов - вы получите предупреждение.
- Как только вы доберетесь до комнаты-цели - игра будет завершена.
- Есть опциональный счетчик шагов.

## Установка необходимых библиотек

Для удобства все библиотеки собраны в requirements.txt.
Чтобы автоматически установить их введите в терминале:

```
pip install -r requirements.txt
```

## Запуск проекта

Запускать проект следует через - `main.py`

Для установки переменной используйте `set FLASK_APP=main.py` (под Windows)
