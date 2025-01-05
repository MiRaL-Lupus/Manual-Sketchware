

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

Раздел Math:


1. getDip ()


2. getDisplayWidthPixels


3. getDisplayHeightPixels


4. PI(π)


5. E(e)


6. to the power () ()


7. minimum of () and ()


8. maximum of () and ()


9. square root of ()


10. absolute value of ()


11. round ()


12. ceil ()


13. floor ()


14. sin ()


15. cos ()


16. tan ()


17. arcsin ()


18. arccos ()


19. arctan ()


20. exp ()


21. ln ()


22. log ()


23. Degree () to Radian


24. Radian () to Degree


---

Раздел File

1. resize image retain ratio from path [] to path [] max size ()


2. resize image to square from path [] to path [] max size ()


3. resize image to circle from path [] to path []


4. resize image rounded from path [] to path [] round pixels ()


5. crop image center from path [] to path [] width () height ()


6. rotate image from path [] to path [] angle ()


7. scale image from path [] to path [] x () y ()


8. skew image from path [] to path []


9. set image color filter from path [] to path [] color Color: ↓


10. set image brightness from path [] to path [] value ()


11. set image contrast from path [] to path [] value ()


12. file list in path [] to List String: ↓


13. make directory path []


14. rename file path [] to []


15. delete file path []


16. move file path [] to path []


17. copy dir path [] to path []


18. copy file path [] to path []


19. write String [] to file path []


20. File: ↓ canExecute


21. File: ↓ canRead


22. File: ↓ canWrite


23. File: ↓ getName


24. File: ↓ getParent


25. File: ↓ getPath


26. File: ↓ isHidden


27. is exist file path []


28. get jpeg rotate from file path []


29. read file path []


30. path [] is directory


31. path [] is file


32. get length of path []


33. path [] starts with []


34. path [] ends with []


35. get last segment path of []


36. get external storage directory


37. get package data directory


38. get public directory type directoryType: ↓


---
Раздел View:
основные блоки:

1. View: ↓ setEnable


2. visibility of View: ↓ equals visible: ↓


3. View: ↓ setVisible visible: ↓


4. View: ↓ setElevation ()


5. View: ↓ getEnable


6. View: ↓ setRotation ()


7. View: ↓ getRotation


8. View: ↓ setAlpha ()


9. View: ↓ getAlpha


10. View: ↓ setTranslationX ()


11. View: ↓ getTranslationX


12. View: ↓ setTranslationY ()


13. View: ↓ getTranslationY


14. View: ↓ setScaleX ()


15. View: ↓ getScaleX


16. View: ↓ setScaleY ()


17. View: ↓ getScaleY


18. View: ↓ request focus


19. View: ↓ getLocationX


20. View: ↓ getLocationY


21. View: ↓ getHeight


22. View: ↓ getWidth


23. View: ↓ removeView View: ↓


24. View: ↓ removeAllViews


25. View: ↓ addView View: ↓


26. View: ↓ addView View: ↓ index ()


27. View: ↓ setGravity gravity_v: ↓ gravity_h: ↓


28. View: ↓ setColorFilter Color: ↓ with porterduff: ↓


29. View: ↓ setBackgroundColor Color: ↓


30. View: ↓ setBackgroundResource BackgroundImage: ↓


31. View: ↓ setBackgroundDrawable drawable: ↓


32. View: ↓ setStroke strokeColor Color: ↓ bgColor Color: ↓


33. View: ↓ setCornerRadius color Color: ↓


34. View: ↓ setGradientBackground Color: ↓ and Color: ↓


35. View: ↓ getChildAt ()

 Блоки Witgets:






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
