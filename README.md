# Инструмент для анализа клиентских данных

### 1. Подвязана локальная база данных `SQLite`.
  * Организовано хранение данных, которые были импортированы из выбранного пользователем csv-файла.
  * Реализована функция сохранения данных, которые были импортированы из выбранного пользователем csv-файла.
  * Данные сохраняются в трёх случаях:
    * При начальном импорте `csv-файла`.
    * При нажатии на кнопку сохранения данных.
    * Перед закрытием приложения.

### 2. Поле выбора **"Построить график"** представляет собой список из доступных типов графиков:
  * Линейный график.
  * Диаграмма рассеяния.
  * Линейный график.
  * Столбчатая диаграмма.
  * Круговая диаграмма.

Также теперь для каждого из типа графика можно `выбрать столбец`, по которому этот график будет построен.

### 3. Добавлена возможность **редактирования полей столбцов**. 
  * Также добавлена **валидация данных после изменения** (то есть, если пользователь изменит число на строку и затем попытается создать график по этому столбцу - выпадет предупреждение).
  * Синхронизирована кодировка. Благодаря этому теперь нет ошибок `invalid syntax` при использовании кириллицы в полях столбцов.

## Скриншоты приложения:

![image](https://github.com/user-attachments/assets/da5b0dcd-2d52-4cb5-906a-7ed101bfcb0d)
![image](https://github.com/user-attachments/assets/7114b210-6474-4d8a-bb5c-34c7137e6d79)
