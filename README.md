

Manual-Sketchware Pro

Полный мануал для работы с программой Sketchware Pro, включающий основные инструкции, функции и описание блоков.


---

Содержание

1. Создание проекта


2. Конструкторская часть


3. Раздел View


4. Раздел Component


5. Раздел MoreBlock


6. Раздел Variable


7. Раздел List


8. Шпаргалка для написания блоков




---

Создание проекта

1. Основной экран:

Enter application name: Ввод названия приложения.

Change Icon: Изменение иконки приложения.

Advanced Settings: Настройка проекта (имя пакета, версия, цвета).



2. Advanced Settings:

Цветовая тема:

colorAccent: Цвет акцентных элементов.

colorPrimary: Основной цвет приложения.

colorPrimaryDark: Цвет статус-бара.






---

Конструкторская часть

1. Тулбар:

View: Редактирование интерфейса.

Event: Настройка событий и логики.

Component: Настройка компонентов.

Undo/Redo: Отмена и повтор изменений.

Save: Сохранение проекта.



2. Функции меню:

Library, View, Image, Sound, Font.





---

Раздел View

1. Layouts:

Linear(H), Linear(V), Scroll(H), Scroll(V).



2. Widgets:

Button, TextView, EditText, ImageView, CheckBox, RadioButton.



3. Progress & Media:

ProgressBar, VideoView, WebView.



4. List:

ListView, RecyclerView, Spinner.



5. AndroidX:

CardView, TabLayout, BottomNavigationView.





---

Раздел Component

Компоненты:

Intent, SharedPreferences, Calendar, Vibrator.

Timer, Dialog, MediaPlayer, SoundPool.

Firebase DB, Firebase Auth, Firebase Storage.




---

Раздел MoreBlock

1. Типы переменных:

Boolean, Number, String, Map.

List Number, List String, List Map.



2. Типы View:

TextView, ImageView, CheckBox.



3. Типы Component:

Intent, Dialog, MediaPlayer.





---

Раздел Variable

1. Boolean:

VOID - set Boolean: ↓ to <>



2. Number:

VOID - set Number: ↓ to ()

VOID - Number: ↓ increase 1



3. String:

VOID - set String: ↓ to []



4. Map:

VOID - Map: ↓ create new map

STRING - Map: ↓ get key []

NUMBER - Map: ↓ get number key []





---

Раздел List

1. List Number:

BOOLEAN - List Number: ↓ contains ()

NUMBER - get at () of List Number: ↓



2. List String:

BOOLEAN - List String: ↓ contains []

STRING - get at [] of List String: ↓



3. Общие операции:

NUMBER - length of List: ↓

VOID - shuffle List: ↓





---

Шпаргалка для написания блоков

1. Форма вставки значений:

<>: Boolean (шестиугольник).

(): Number (овал).

[]: String (прямоугольник).

↓: Выпадающее меню.



2. Структура записи блоков:

Пример сложного блока:
VOID - Custom_Block <> () [] List Number: ↓



