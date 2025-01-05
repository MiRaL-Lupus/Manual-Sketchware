

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



set Boolean: <> to <>

set Number: <> to ()

Number: increase 1, decrease 1

set String: <> to []

Map: create new map

Map: put key [] value []

Map: put key [] value ()

Map: put key [] value double ()

Map: put key [] value <>

Map: put key [] value Map: ↓

Map: put key [] value List String: ↓

Map: put key [] value List Map: ↓

Map: get key []

Map: get number key ()

Map: get boolean key <>

Map: get Map key Map: ↓

Map: get List String key List String: ↓

Map: get List Map key List Map: ↓

Map: is empty <>

Map: contain key []

Map: contain value []

Map: size ()

Map: remove key []

Map: clear

Map: get all keys to List String: ↓




---

Раздел List



List Number: contains ()

List Number: get at () of List Number: ↓

List Number: index () in List Number: ↓

List Number: add () to List Number: ↓

List Number: insert () at () to List Number: ↓

List Number: set () at () of List Number: ↓

List Number: sort List Number: ↓

List String: contains []

List String: index [] in List String: ↓

List String: get at () of List String: ↓

List String: add [] to List String: ↓

List String: insert [] at () to List String: ↓

List String: set [] at () of List String: ↓

List String: sort List String: ↓

List: addAll from List: ↓

List: delete at () of List: ↓

List: clear List: ↓

List: reverse List: ↓

List: shuffle List: ↓

List: swap List: ↓ position () with ()

List: length of List: ↓

List Map: contains at () key []

List Map: get value at [] key () of List Map: ↓

List Map: get Map at () of List Map: ↓

List Map: add key [] value [] to List Map: ↓

List Map: insert key [] value [] at () to List Map: ↓

List Map: set key [] value [] at () to List Map: ↓

List Map: set Map: ↓ at () of List Map: ↓

List Map: add Map: ↓ to List Map: ↓

List Map: insert Map: ↓ at () to List Map: ↓

List Map: get at () of List Map: ↓ to Map: ↓

List Map: delete Map: ↓ of List Map: ↓

List Map: sort List Map: ↓ key () isNumber <> isAscending <>


---
Раздел Control:

1. Управление циклами:

repeat ()

repeat () ++

repeat () --

forever

while <>



2. Условия:

if <> then

if <> then else

switch []

case [] and

case () and



3. Обработка исключений:

try

catch



4. Возврат значений:

return []

return ()

return <>

return Map: ↓

return List String: ↓

return List Map: ↓

return View: ↓



5. Поток управления:

stop

continue



6. Логика:

instanceOf <>

isEmpty <>

<boolean> ? :

() ? :


---

Раздел Operator:


блоки Boolean (имеют форму шестиугольников):

------

true

false

() < ()

<> and <>

<> or <>

<> not <>

блоки Number (имеют форму овала):

() + ()

() - ()

() * ()

() / ()

() % ()

------

продолжение раздела Operator:


pick random () to ()

length of []

join [] and []

index of [] in []

last index of [] in []

substring [] to []

subString []

equals [] []

contains []

matches RegExp []

replace all [] with []

replace all RegEx [] with []

replace first RegEx [] with []

reverse []

html []

trim []

toUpperCase []

toLowerCase []

toNumber []

parse int []

toHashCode []

toString () without decimal

toString () with decimal

toDecimalFormat []

JSON [] to Map: ↓

Map: ↓ to JSON String

JSON [] to List Map: ↓

List Map: ↓ to JSON String

JSON [] to List String: ↓

JSON [] to List Number: ↓

List: ↓ to JSON String

split [] RegExp [] into List String: ↓

add source directly []


---



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
