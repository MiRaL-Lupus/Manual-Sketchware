

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

1. TextView: ↓ setText []


2. TextView: ↓ setTypeface font: ↓ with style typeface: ↓


3. TextView: ↓ setTextColor Color: ↓


4. TextView: ↓ setTextSize ()


5. EditText: ↓ set hint text to []


6. EditText: ↓ set hint color to Color: ↓


7. EditText: ↓ disable suggestions


8. EditText: ↓ set lines ()


9. EditText: ↓ singleLine <>


10. EditText: ↓ show error []


11. EditText: ↓ select all text


12. EditText: ↓ set selection start () end ()


13. EditText: ↓ set max lines ()


14. EditText: ↓ get selection start


15. EditText: ↓ get selection end


16. TextView: ↓ getText


17. CheckBox: ↓ setChecked <>


18. CheckBox: ↓ getChecked


19. AutoComplete: ↓ setListData List String: ↓


20. MultiAutoComplete: ↓ setListData List String: ↓


21. MultiAutoComplete: ↓ setThreshold ()


22. MultiAutoComplete: ↓ CommaTokenizer


23. ImageView: ↓ setImage Image: ↓


24. ImageView: ↓ setImage image: ↓


25. ImageView: ↓ set image by name []


26. ImageView: ↓ set image from file path []


27. ImageView: ↓ set image from url []


28. ImageView: ↓ setColorFilter Color: ↓


29. RatingBar: ↓ setRating ()


30. RatingBar: ↓ setNumStars ()


31. RatingBar: ↓ setStepSize ()


32. RatingBar: ↓ getRating


33. SeekBar: ↓ setProgress ()


34. SeekBar: ↓ setMax ()


35. SeekBar: ↓ getProgress


36. SeekBar: ↓ getMax


37. ProgressBar: ↓ setIndeterminate <>


38. VideoView: ↓ setVideoUri []


39. VideoView: ↓ start


40. VideoView: ↓ pause


41. VideoView: ↓ stopPlayback


42. VideoView: ↓ isPlaying <>


43. VideoView: ↓ canSeekForward <>


44. VideoView: ↓ canSeekBackward <>


45. VideoView: ↓ getCurrentPosition


46. VideoView: ↓ getDuration


47. WebView: ↓ loadUrl []


48. WebView: ↓ setCacheMode cacheMode: ↓


49. WebView: ↓ goBack


50. WebView: ↓ goForward


51. WebView: ↓ clearCache


52. WebView: ↓ clearHistory


53. WebView: ↓ stopLoading


54. WebView: ↓ getUrl


55. WebView: ↓ getProgress


56. WebView: ↓ canGoBack <>


57. WebView: ↓ canGoForward <>


58. WebView: ↓ zoomIn


59. WebView: ↓ zoomOut


блоки List:

1. Spinner: ↓ setSpinnerData List String: ↓


2. Spinner: ↓ setSpinnerCustomViewData List Map: ↓


3. Spinner: ↓ refreshData


4. Spinner: ↓ setSelection ()


5. Spinner: ↓ getSelection


6. ListView: ↓ setListViewData List String: ↓


7. ListView: ↓ setListCustomViewData List Map: ↓


8. ListView: ↓ refreshData


9. ListView: ↓ invalidate views


10. ListView: ↓ smoothScrollToPosition ()


11. ListView: ↓ set selection ()


12. ListView: ↓ setTranscriptMode transcriptmode: ↓


13. ListView: ↓ setStackFromBottom <>


14. ListView: ↓ add Header view View: ↓ data [] selectable? <>


15. ListView: ↓ remove Header View: ↓


16. ListView: ↓ add Footer view View: ↓ data [] selectable? <>


17. ListView: ↓ remove Footer View: ↓


18. RecyclerView: ↓ setRecyclerCustomViewData List Map: ↓


19. RecyclerView: ↓ setLayoutManager


20. RecyclerView: ↓ set Horizontal LayoutManager


21. RecyclerView: ↓ setHasFixedSize <>


22. RecyclerView: ↓ smoothScrollToPosition ()


23. RecyclerView: ↓ scrollToPosition () offset ()


24. GridView: ↓ setGridCustomViewData List Map: ↓


25. GridView: ↓ setNumColumns ()


26. GridView: ↓ setColumnWidth ()


27. GridView: ↓ setVerticalSpacing ()


28. GridView: ↓ setHorizontalSpacing ()


29. GridView: ↓ setStretchMode gridstretchmode: ↓


30. ViewPager: ↓ setPagerCustomViewData List Map: ↓


31. ViewPager: ↓ setFragmentAdapter FragmentAdapter: ↓ TabCount ()


32. ViewPager: ↓ setOffscreenPageLimit ()


33. ViewPager: ↓ setCurrentItem ()


34. ViewPager: ↓ notifyDataSetChanged


35. ViewPager: ↓ getOffscreenPageLimit


36. ViewPager: ↓ getCurrentItem


 блоки AndroidX Component:

1. BottomNavigation: ↓ add item id () title [] icon Image: ↓


2. When SwipeRefreshLayout: ↓ refreshed


3. SwipeRefreshLayout: ↓ setRefreshing <>


4. CardView: ↓ setCardBackgroundColor Color: ↓


5. CardView: ↓ setCornerRadius ()


6. CardView: ↓ setCardElevation ()


7. CardView: ↓ setPreventCornerOverlap <>


8. CardView: ↓ setUseCompatPadding <>


9. TabLayout: ↓ addTabTitle []


10. TabLayout: ↓ setupWithViewPager ViewPager: ↓


11. TabLayout: ↓ setInlineLabel <>


12. TabLayout: ↓ setTabTextColors Normal Color: ↓ Selected Color: ↓


13. TabLayout: ↓ setTabRippleColor Color: ↓


14. TabLayout: ↓ setSelectedTabIndicatorColor Color: ↓


15. TabLayout: ↓ setSelectedTabIndicatorHeight ()


16. TextInputLayout: ↓ setBoxBackgroundColor Color: ↓


17. TextInputLayout: ↓ setBoxStrokeColor Color: ↓


18. TextInputLayout: ↓ setBoxBackgroundMode til_box_mode: ↓


19. TextInputLayout: ↓ setBoxCornerRadius TL () TR () BL () BR ()


20. TextInputLayout: ↓ setError []


21. TextInputLayout: ↓ setErrorEnabled <>


22. TextInputLayout: ↓ setCounterEnabled <>


23. TextInputLayout: ↓ setCounterMaxLength ()


24. TextInputLayout: ↓ getCounterMaxLength


блоки Library:

1. OTPView: ↓ setFieldCount ()


2. OTPView: ↓ setOTPText []


3. OTPView: ↓ onOTPEntered -> _otp


4. OTPView: ↓ getOTPText


5. BadgeView: ↓ getBadgeCount


6. BadgeView: ↓ setBadgeNumber ()


7. BadgeView: ↓ setBadgeString []


8. BadgeView: ↓ setBadgeBackground Color: ↓


9. BadgeView: ↓ setBadgeTextColor Color: ↓


10. BadgeView: ↓ setBadgeTextSize ()


11. WaveSideBar: ↓ setCustomLetter String: []


12. BubbleLayout View: ↓ setBubbleColor Color: ↓


13. BubbleLayout View: ↓ setStrokeColor Color: ↓


14. BubbleLayout View: ↓ setStrokeWidth ()


15. BubbleLayout View: ↓ setCornerRadius ()


16. BubbleLayout View: ↓ setArrowHeight ()


17. BubbleLayout View: ↓ setArrowWidth ()


18. BubbleLayout View: ↓ setArrowPosition ()


19. PatternLockView: ↓ setDotCount ()


20. PatternLockView: ↓ setNormalStateColor Color: ↓


21. PatternLockView: ↓ setCorrectStateColor Color: ↓


22. PatternLockView: ↓ setWrongStateColor Color: ↓


23. PatternLockView: ↓ setViewMode patternviewmode: ↓


24. PatternLockView: ↓ clearPattern


25. CodeView: ↓ setCode []


26. CodeView: ↓ setLanguage cv_language: ↓


27. CodeView: ↓ setTheme cv_theme: ↓


28. CodeView: ↓ apply


29. LottieAnimation: ↓ setAnimationFromAsset []


30. LottieAnimation: ↓ setAnimationFromJson []


31. LottieAnimation: ↓ setAnimationFromUrl []


32. LottieAnimation: ↓ setRepeatCount ()


33. LottieAnimation: ↓ setSpeed ()


34. PatternLockView: ↓ getPattern from List String: ↓ to String


35. PatternLockView: ↓ getPattern from List String: ↓ to MD5


36. PatternLockView: ↓ getPattern from List String: ↓ to SHA1


блоки Goggle:

1. SignInButton: ↓ setColorScheme SignButtonColor: ↓


2. SignInButton: ↓ setSize SignButtonSize: ↓


3. YouTubePlayer: ↓ geLifecycle


4. YouTubePlayer: ↓ addYouTubePlayerListener VideoID: []


5. MapView: ↓ set Map type mapType: ↓


6. MapView: ↓ move camera lat () lng ()


7. MapView: ↓ zoom to ()


8. MapView: ↓ zoom in


9. MapView: ↓ zoom out


10. MapView: ↓ add marker id [] position lat () lng ()


11. MapView: ↓ marker id [] set title [] snippet []


12. MapView: ↓ marker id [] set position lat () lng ()


13. MapView: ↓ marker id [] set color markerColor: ↓ alpha ()


14. MapView: ↓ marker id [] set icon Image: ↓


15. MapView: ↓ marker id [] set visible <>


блоки Date & Time:

1. TimePicker: ↓ setHour ()


2. TimePicker: ↓ setMinute ()


3. TimePicker: ↓ setCurrentHour ()


4. TimePicker: ↓ setCurrentMinute ()


5. TimePicker: ↓ setIs24Hour <>


6. CalendarView: ↓ setDate () ms


7. CalendarView: ↓ setMinDate () ms


8. CalendarView: ↓ setMaxDate () ms


блоки Function:

1. View: ↓ performClick


2. When View: ↓ clicked


3. When View: ↓ long clicked


4. When View: ↓ touched


5. View: ↓ showSnackbar text [] actionText [] onClick


--- конец раздела View ---

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
