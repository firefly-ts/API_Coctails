**Индивидуальный проект для ОС Android версии 8.0 и выше для демонстрации навыков разработки и подтверждения компетенции педагога ИТ школы Samsung.**

**Обязательные требования**
 Необходимо использовать многопоточность. В проекте использован AsyncTask при получении необходимых данных с сайта с api
 Необходимо использовать БД + любую стороннюю библиотеку ИЛИ сервисы Firebase Использована встроенная БД SQLite. В проекте есть сохранение в локальную БД SQLite и использованы сторонние бибилиотеки Volley и Picasso
 В интерфейсе одной из активностей/фрагментов должен быть реализован список ListView/RecyclerView Реализован список RecyclerView, отображающий результаты работы потоков.

**Что приложение делает?**
В приложении имеется три экрана. 
На первом загружается случайный коктейль и набор кнопок для поиска коктейлей по первой букве. При нажатии кнопки переходим на второй экран, где идёт загрузка с сайта всех коктейлей на эту букву.
При выборе (на основании "тапа") соответствующий коктейль вносится в локальную БД.
Посмотреть сохранённые коктейли можно при переходе с первого экрана по кнопке "Favorite cocktails".
На третьем экране загружаются все избранные коктейли. Реализована очистка списка при помощи соответствующей кнопки.


Приложение корректно отрабатывает переход в фоновый режим и обратно. Список избраного сохраняется в БД SQLite.
