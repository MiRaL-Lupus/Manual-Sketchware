# Manual-Sketchware

1. Создание проекта

Основной экран:

Enter application name: Ввод названия приложения, которое вы создаёте.

Change Icon: Возможность изменить иконку приложения, нажав на значок Android.

Advanced Settings: Расширенные настройки проекта (доступны при нажатии на шестерёнку).

Package name: Уникальное имя пакета приложения в формате com.example.projectname.

Project name: Имя проекта, отображаемое внутри Sketchware.

Version: Номер версии приложения в формате Major.Minor.


Расширенные настройки (Advanced Settings):

Настройка цветовой темы:

colorAccent: Цвет акцентных элементов (например, кнопок или переключателей).

colorPrimary: Основной цвет приложения (обычно цвет заголовка).

colorPrimaryDark: Тёмный оттенок основного цвета (используется для статус-бара).



Дополнительные объяснения:

colorPrimaryDark: Цвет статус-бара.

colorPrimary: Основной цвет заголовка приложения.

colorAccent: Цвет акцентных элементов, таких как кнопки и выделения.

colorControlHighlight: Цвет подсветки элементов управления (например, нажатия на кнопки).

colorControlNormal: Цвет обычных состояний элементов управления.


2. Конструкторская часть

Тулбар:

Название проекта: Отображается текущий проект (например, NewProject5).

606: Индикатор текущего экрана или страницы.

Кнопки управления:

View: Переход к экрану редактирования визуальной части приложения.

Event: Переход к настройке событий и логики (действий).

Component: Настройка компонентов приложения (например, базы данных, анимаций).


Стрелка влево: Возврат к предыдущему экрану.

Undo/Redo: Кнопки отмены/повторения изменений.

Save: Сохранение изменений в проекте.

Три точки: Открытие дополнительных функций и настроек.


Функции в меню:

Library: Настройки компонентов библиотеки.

View: Управление несколькими экранами.

Image: Импорт изображений и иконок.

Sound: Импорт музыкальных файлов и звуковых эффектов.

Font: Добавление пользовательских шрифтов.

Java/Kotlin: Импорт пользовательских Java/Kotlin файлов.

Resource: Импорт файлов ресурсов.

Asset: Импорт файлов, используемых в проекте.

Permission: Настройка пользовательских разрешений.

AppCompat: Модификация макетов AppCompat.

AndroidManifest: Редактирование AndroidManifest.xml.

Custom Blocks: Просмотр пользовательских блоков.

Local library: Добавление локальных библиотек.

Native library: Добавление нативных библиотек (.so).

ProGuard: Минимизация/обфускация приложения.

StringFog: Шифрование строк в приложении.

Show Source Code: Просмотр Java и XML файлов проекта.

Logcat Reader: Чтение логов отладочной информации.

Collection: Доступ к сохранённым коллекциям.


3. Раздел View — Элементы для добавления на холст программы:

Layouts:

1. Linear(H) — Горизонтальный линейный макет.


2. Linear(V) — Вертикальный линейный макет.


3. Scroll(H) — Горизонтальный скроллируемый макет.


4. Scroll(V) — Вертикальный скроллируемый макет.


5. RadioGroup — Группа переключателей (радио-кнопок).



AndroidX:

1. TabLayout — Макет с вкладками.


2. BottomNavigationView — Панель нижней навигации.


3. CollapsingToolbar — Сворачиваемая панель инструментов.


4. CardView — Карточный макет.


5. TextInputLayout — Макет для ввода текста с подсказками.


6. SwipeRefreshLayout — Обновление страницы свайпом вниз.



Widgets:

1. TextView — Элемент отображения текста.


2. EditText — Поле для ввода текста.


3. AutoCompleteTextView — Поле ввода с автозаполнением.


4. MultiAutoCompleteTextView — Поле ввода с несколькими вариантами автозаполнения.


5. Button — Кнопка.


6. MaterialButton — Кнопка в стиле Material Design.


7. ImageView — Изображение.


8. CircleImageView — Круглое изображение.


9. CheckBox — Флажок.


10. RadioButton — Радио-кнопка.


11. Switch — Переключатель.


12. SeekBar — Ползунок для выбора значения.


Progress & Media:

1. ProgressBar — Индикатор прогресса.


2. RatingBar — Полоса рейтинга.


3. SearchView — Поле поиска.


4. VideoView — Видеоплеер.


5. WebView — Веб-браузер.



List:

1. ListView — Список.


2. GridView — Сетка.


3. RecyclerView — Список с возможностью обновления.


4. Spinner — Выпадающий список.


5. ViewPager — Страницы с возможностью перелистывания.



Library:

1. BadgeView — Элемент с меткой.


2. WaveSideBar — Боковая панель с волной.


3. PatternLockView — Шаблон блокировки.


4. CodeView — Отображение кода.


5. LottieAnimation — Анимации Lottie.


6. OTPView — Вид для ввода одноразовых паролей.



Google:

1. AdView — Реклама Google AdMob.


2. MapView — Карты Google.


3. SignInButton — Кнопка авторизации через Google.


4. YoutubePlayer — Видеоплеер YouTube.



Date & Time:

1. AnalogClock — Аналоговые часы.


2. DigitalClock — Цифровые часы.


3. TimePicker — Выбор времени.


4. DatePicker — Выбор даты.


5. CalendarView — Календарь.


4. Панель в разделе View и настройки Build Settings

Панель управления внизу:

main.xml: Название текущего открытого XML-файла.

3 полоски (иконка): Кнопка, открывающая дополнительное меню.

Run: Кнопка запуска приложения.


Меню из кнопки с 3 полосками:

Build Settings: Настройка сборки проекта.

Clean temporary files: Очистка временных файлов.

Show last compile error: Отображение последней ошибки компиляции.

Show source code: Просмотр исходного кода проекта.


Список файлов XML:

При нажатии на текущий файл (например, main.xml) появляется список всех доступных XML-файлов.

Кнопка "+": Открывает окно для создания новой активности.


Создание новой активности:

Enter View name: Поле для ввода имени новой активности.

Опции интерфейса:

StatusBar: Включение или отключение строки состояния.

Toolbar: Добавление панели инструментов.

Drawer: Включение боковой панели.

FAB: Добавление кнопки быстрого доступа (Floating Action Button).


Тип активности (Type):

Activity: Обычная активность.

Fragment: Фрагмент.

DialogFragment: Диалоговое окно.


Ориентация экрана (Screen Orientation):

Portrait: Портретная ориентация.

Landscape: Альбомная ориентация.

Both: Поддержка обеих ориентаций.


Настройки клавиатуры (Keyboard Settings):

Unspecified: Без конкретных настроек.

Visible: Клавиатура отображается.

Hidden: Клавиатура скрыта.



Окно Build Settings:

Custom android.jar: Поле для ввода пути к пользовательскому файлу android.jar.

Classpath: Поле для ввода путей к классам (разделённых двоеточием).

Dexer:

Dx: Использовать стандартный инструмент для преобразования файлов.

D8: Использовать более современный инструмент Dex.


Java version:

Опции: 1.7, 1.8, 1.9, 10, 11.


Флажки:

Hide warnings in error log: Скрытие предупреждений в журнале ошибок.

Don't include http-legacy-28.dex: Исключение файла http-legacy-28.dex.

Enable debug logcat logs viewable in Logcat Reader: Включение отладочных логов, доступных через Logcat Reader.


Кнопки:

Cancel: Отмена изменений.

Save: Сохранение настроек.

Sketchware Manual (продолжение)

5. Раздел Component

Пустой экран при входе: При переходе в раздел Component, изначально отображается пустой экран с кнопкой "+", предназначенной для добавления новых компонентов.

Меню кнопки "+":

1. Intent: Создание намерений для перехода между экранами или внешними приложениями.


2. SharedPreferences: Сохранение данных приложения в локальной памяти.


3. Calendar: Работа с календарными событиями.


4. Vibrator: Управление вибрацией устройства.


5. Timer: Таймер для отсчёта времени.


6. Dialog: Создание диалоговых окон.


7. MediaPlayer: Воспроизведение аудиофайлов.


8. SoundPool: Управление звуковыми эффектами.


9. ObjectAnimator: Анимация объектов.


10. Camera: Управление камерой устройства.


11. FilePicker: Выбор файлов с устройства.


12. Gyroscope: Использование гироскопа устройства.


13. Firebase DB: Работа с базой данных Firebase.


14. Firebase Auth: Аутентификация через Firebase.


15. Firebase Storage: Хранение файлов на Firebase.


16. Interstitial Ad: Показ межстраничных рекламных объявлений.


17. TextToSpeech: Преобразование текста в речь.


18. SpeechToText: Преобразование речи в текст.


19. RequestNetwork: Отправка сетевых запросов.


20. BluetoothConnect: Подключение через Bluetooth.


21. LocationManager: Управление геолокацией.


22. RewardedVideoAd: Видеообъявления с вознаграждением.


23. ProgressDialog: Диалог загрузки с индикатором.


24. DatePickerDialog: Диалог выбора даты.


25. TimePickerDialog: Диалог выбора времени.


26. Notification: Отправка уведомлений.


27. FragmentAdapter: Адаптер для работы с фрагментами.


28. AsyncTask: Асинхронная работа с задачами.





---

6. Раздел MoreBlock

При создании нового блока в разделе MoreBlock, в опции Add Variable есть 3 категории:


1. Категория - Variable:

Boolean

Number

String

Map

List Number

List String

List Map



2. Категория - View:

View

TextView

ImageView

CheckBox

Switch

ListView

Spinner

WebView

SeekBar

ProgressBar

CalendarView

RadioButton

RatingBar

VideoView

SearchView

GridView

AutoComplete

MultiAutoComplete

ViewPager

BadgeView



3. Категория - Component:

Intent

SharedPreferences

Calendar

Vibrator

Timer

Dialog

MediaPlayer

SoundPool

ObjectAnimator

Firebase DB

Firebase Auth

Firebase Storage

Camera

FilePicker

RequestNetwork

TextToSpeech

SpeechToText

LocationManager

VideoAd

ProgressDialog

TimePickerDialog

Notification





---

7. Раздел Variable

VOID - set Boolean: ↓ to <>

VOID - set Number: ↓ to ()

VOID - Number: ↓ increase 1

VOID - Number: ↓ decrease 1

VOID - set String: ↓ to []

VOID - Map: ↓ create new map

VOID - Map: ↓ put key [] value []

VOID - Map: ↓ put key [] value ()

VOID - Map: ↓ put key [] value <>

VOID - Map: ↓ put key [] value Map: ↓

VOID - Map: ↓ put key [] value List String: ↓

VOID - Map: ↓ put key [] value List Map: ↓

STRING - Map: ↓ get key []

NUMBER - Map: ↓ get number key []

BOOLEAN - Map: ↓ get boolean key []

MAP - Map: ↓ get Map key []

List String - Map: ↓ get List String key []

List Map - Map: ↓ get List Map key []

BOOLEAN - Map: ↓ is empty

BOOLEAN - Map: ↓ contain key []

BOOLEAN - Map: ↓ contain value []

NUMBER - Map: ↓ size

VOID - Map: ↓ remove key []

VOID - Map: ↓ clear

List String - Map: ↓ get all keys to List String: ↓



---

8. Раздел List

List Number:

1. List Number: ↓ contains ()


2. get at () of List Number: ↓


3. index () in List Number: ↓


4. add () to List Number: ↓


5. insert () at () to List Number: ↓


6. set () at () of List Number: ↓


7. sort List Number: ↓



List String: 8. contains [] 9. index [] in List String: ↓ 10. get at [] of List String: ↓ 11. add [] to List String: ↓ 12. insert [] at () to List String: ↓ 13. set [] at () of List String: ↓ 14. sort List String: ↓

List Map: 15. contains at () key 16. get value at () key of List Map: ↓ 17. get Map at () of List Map: ↓ 18. add key [] value [] to List Map: ↓ 19. insert key [] value [] at () to List Map: ↓ 20. set key [] value [] at () to List Map: ↓ 21. set Map: ↓ at () of List Map: ↓ 22. add Map: ↓ to List Map: ↓ 23. insert Map: ↓ at () to List Map: ↓ 24. get at () of List Map: ↓ to Map: ↓ 25. delete Map: ↓ of List Map: ↓ 26. sort List Map: ↓ key <> isNumber <> isAscending <>

General: 27. length of List: ↓ 28. addAll from List: ↓ 29. delete at () of List: ↓ 30. clear List: ↓ 31. reverse List: ↓ 32. shuffle List: ↓ 33. swap List: ↓ position () with ()



