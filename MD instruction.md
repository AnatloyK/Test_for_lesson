# Синтаксис языка Markdown

[Справочник по Markdown от Microsoft: <https://docs.microsoft.com/ru-ru/contribute/markdown-reference> или [ссылка](https://docs.microsoft.com/ru-ru/contribute/markdown-reference).

* Установка Git для Windows, MAC, Linux: <https://git-scm.com/downloads> или [ссылка](https://git-scm.com/downloads);

* Установка VSCode для Windows, MAC, Linux: <https://code.visualstudio.com/Download> или [ссылка](https://code.visualstudio.com/Download
);

>При первом использовании Git необходимо представиться. Для этого нужно ввести в терминале 2 команды:

>>* <span style="color: blue"> git config --global user.name «Ваше имя английскими буквами»

>>* <span style="color: blue"> git config --global user.email ваша почта@example.com

---

# Основные команды Git

* <span style="color: blue"> git init</span> – инициализация локального репозитория;

* <span style="color: blue">git status</span> – получить информацию от git о его текущем состоянии;

* <span style="color: blue">git add</span> – добавить файл или файлы к следующему коммиту;

* <span style="color: blue">git commit -m “message”</span> – создание коммита;

* <span style="color: blue">git log</span> – вывод на экран истории всех коммитов с их хеш-кодами;

* <span style="color: blue">git checkout</span> – переход от одного коммита к другому;

* <span style="color: blue">git checkout master</span> – вернуться к актуальному состоянию и продолжить работу;

* <span style="color: blue">git diff</span> – увидеть разницу между текущим файлом и закоммиченным файлом

---

# Синтаксис языка Markdown

Справочник по Markdown от Microsoft:
<https://docs.microsoft.com/ru-ru/contribute/markdown-reference>

* <span style="color: blue">#Заголовок</span> – выделение заголовков. Количество символов “#” задаёт уровень заголовка  (поддерживается 6 уровней).

* <span style="color: blue">= или -</span> – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки  первого (“=”) и второго (“-”) уровней.

* <span style="color: blue">**Полужирное начертание**</span> или <span style="color: blue">**Полужирное начертание**</span>

* <span style="color: blue">*Курсивное начертание*</span> или <span style="color: blue">*Курсивное начертание*</span>

* <span style="color: blue">***Полужирное курсивное начертание***</span>

* <span style="color: blue">~~ Зачёркнутый текст ~~</span>

* <span style="color: blue">*Строка</span> – ненумерованные списки, символ “*” в начале строки

* <span style="color: blue">1, 2, 3 …</span> – нумерованные списки

---

# Выделение текста

# Списки

# Работа с изображениями

# Ссылки

Для создания геперссылок используется комбинация из квадратных и круглых скобок. В квадратных скобках указывается текст, а в круглых - URL ссылки.

Пример [ссылка на сайт] (https://youtube.com/) будет выглядеть как [youtube ссылка](https://youtube.com/)

# Работа с таблицами

Для рисования таблиц используются символы | и -. Для указания выравнивания в колонке к последовательности из - добавляются символы :: :--- - влево, :---: - по центру, ---: - вправо.

Наименование | Количество
:----------- | :---------:
Апельсины    | 5
Яблоки       | 120
Груши        | 25

# Цитаты

Цитаты оформляются с помощью символа >.

> Главная проблема цитат в Интернете в том, 
что люди сразу верят в их подлинность
>> Джейсон Стейтем
