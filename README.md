# Инструмент для анализа клиентских данных (RU)

## Функции приложения:

### 1. База данных `SQLite`:
  * Хранение данных, которые были импортированы из выбранного пользователем csv-файла.
  * Сохранения данных, которые были импортированы из выбранного пользователем csv-файла.
  * Данные сохраняются в 3-х случаях:
    * При начальном импорте `csv-файла`.
    * При нажатии на кнопку сохранения данных.
    * Перед закрытием приложения.

### 2. Поле выбора **"Построить график"** представляет собой список из доступных типов графиков:
  * Линейный график.
  * Диаграмма рассеяния.
  * Линейный график.
  * Столбчатая диаграмма.
  * Круговая диаграмма.

Также теперь для каждого из типа графика можно **выбрать столбец**, по которому этот график будет построен.

### 3. Редактирование полей столбцов:
  * После ввода новых данных происходит их **валидация** (то есть, если пользователь изменит число на строку и затем попытается создать график по этому столбцу - выпадет предупреждение).
  * Синхронизирована кодировка. Благодаря этому теперь нет ошибок `invalid syntax` при использовании кириллицы в полях столбцов.

## Скриншоты приложения:

Фронтэнд-интерфейс (пока не встроен в бекэнд):

![client-data-analising-tool](https://github.com/user-attachments/assets/1670b795-0cc3-4086-b6b1-05291ad1060c)

Бекэнд-интерфейс:

![image](https://github.com/user-attachments/assets/da5b0dcd-2d52-4cb5-906a-7ed101bfcb0d)
![image](https://github.com/user-attachments/assets/7114b210-6474-4d8a-bb5c-34c7137e6d79)

## Авторы проекта:

  * [Бедин Владислав](https://github.com/MindlessMuse666 "Владислав: https://github.com/MindlessMuse666"):
    * Team Lead
    * Backend
    * Frontend
  * [Киян Георгий](https://github.com/nineteentearz "Егор: https://github.com/nineteentearz"):
    * Backend
    * Frontend
  * [Вельдяева Александра](https://github.com/FrierenWay "Александра: https://github.com/FrierenWay"):
    * Analyst
    * Software Tester
    * Documentation
    * Database
  * [Букарев Кирилл](https://github.com/bukabtw "Кирилл: https://github.com/bukabtw"):
    * Analyst
    * Software Tester
    * Documentation
    * Database
  * [Гаврилова Дженнет](https://github.com/Jenko-zhulenko "Дженнет: https://github.com/Jenko-zhulenko"): 
    * Frontend
    * UI Designer
    * Project Designer
