
# Журнал инженеров по АСУ

Десктопное приложение для ведения журнала смен инженеров АСУ с поддержкой базы данных PostgreSQL, голосового ввода, экспорта в Word и отправки по email.

## Основные функции
- Авторизация и управление записями в журнале.
- Добавление инженеров на смену.
- Голосовой ввод с визуализацией.
- Экспорт в Word и отправка через Outlook.
- Фильтрация записей.

## Используемые библиотеки
- `psycopg2` — подключение к PostgreSQL.
- `PyQt5` — графический интерфейс.
- `python-docx` — создание Word-документов.
- `pywin32` — интеграция с Outlook.
- `speech_recognition`, `pyaudio` — голосовой ввод.
- `pyqtgraph`, `numpy` — визуализация звука.

## Установка
1. Установите Python 3.8+ и PostgreSQL.
2. Установите зависимости:
   ```bash
   pip install psycopg2-binary PyQt5 python-docx pywin32 speechrecognition pyaudio pyqtgraph numpy

## Склонируйте репозиторий:
  ```bash
  git clone https://github.com/yourusername/ShiftJournal.git

##   Запустите:
  ```bash
   python main.py
