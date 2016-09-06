# Вопросы!

1) Макрос - макрокоманда - макроопределение - в Википедии написано:  программный алгоритм действий, записанный пользователем.
Либо символьный шаблон.
Первое опр-е слишком общее - как понимать?

2) Язык программирования и язык разметки( html, xml) - второй полноправный язык? Или нет?

3) То есть браузер( любой) - это интерпретатор языка разметки( на котором оформлен сайт)?
Значит, html-документ можно открыть только браузером?

4) Сам браузер написан на Java? 

5) TEX - язык разметки низкого уровня (с.10). Что же тогда высокий?html?

6) Latex 2e. Вот это вот е в книге как подстрочный индекс. Why?

7) Термин API важен? По сути, это набор функций, классов в библиотеке?

8) VBA - встроен в Microsoft Office, например, VB - приходилось где-нибудь пользоваться?

9) "Microsoft Visual Basic — язык программирования, а также интегрированная среда разработки программного обеспечения, разрабатываемое корпорацией Microsoft." - то есть вообще понятия "язык программирования" и "среда разработки для этого языка" часто взаимозаменяют?

10) Динамическая и статич. библиотеки. Различия и сходства?

11) Круто! Пакет и библиотека отличаются!

12) Мысли: редактор - доктор VBA.

13) Вопрос дистрибутива: Если я установил программку и она идёт на компьютере 1. 
А затем установленную программку просто перенёс на другой компьютер 2. 
Будет ли работать на 2? Условия.

14) GNU GPL: зачем вводить лицензию на открытое ПО? Из-за авторского права? Непонятно.

15) Верификация, тестирование и отладка - отличия?

16) Открытое и свободное ПО.

17) Жёсткие и символьные ссылки. Бывают ли мягкие? Расскажите поподробнее.

18) Растровая и векторная графика. Не понимаю, ведь от векторной графики мы неизменно будем приходить к растровой на экране в виде пикселей. ?

19) Подсчёт просмотров твоей странички ввк, фикция? На мой первый взгляд, это противоречие КБ и устройства серверов(хиты).

20) Чем отличается макрос от скрипта?

21) Вот это да! Язык ДРАКОН!

22) Допустим, мы разрабатываем систему для редактирования текста. Нам нужно по каким-то расчётам 15 команд редактирования, и этого будет достаточно для универсальной работы в этой системе. Мы можем отдельно их написать("наваять"), отвлекаясь от их совокупности и взаимодействия в системе. Обеспечит ли абсолютная правильность их создания по отдельности корректную работу системы в целом? Либо же всегда нужно их подгонять под совместную работу? Вот такой вот интересный вопрос.

23) Есть ли в интерпретаторе связь текущей команды с ранее выполненными? Например, 1 команда обработалась, выполнена, затем 2-ая, причём в ней содержатся "косвенные" корректировки результата 1-ой команды. Будет ли интерпретатор возвращаться к старому результату и переделывать? Насколько умён интерпретатор? (Вопрос создан при поддержке в одном абзаце \hangindent и \hangafter). То же самое по поводу компилятора.)

24) Что есть системное приложение?

25) На каком языке написана игра Braid? Почему нигде это не упоминается? Почему нет даже намёков на исходный код?

26) Есть ли комбинация горячих клавиш для переключения фокуса на веб-страницах, таких как Youtube, Yandex? (С окна поиска на основное поле, с плеера на поле комментариев? Пока известные мне способы --- это мышкой или клавишей Tab.

#TeX:

###Принципы оформления языка Tex: 

Отступы: Класс документа - отступ - пакеты - отступ - новые команды - отступ - дополнительные опции, команды в преамбуле - двойной отступ - begin.

Команды: Внутри текста бэкслэш идёт сразу после слова, без пробелов, команда, затем пробел. Если много команд подряд, всё без пробелов (воспринимается более цельно, как поток действий + отличается от пробельного массива слов).

Аргументы: После текста команды \textit{сразу} идут первые скобки, затем все последующие через пробел.

###Вопросы:

1) c.21: \documentclass{class1, class2, ...} - можно ли сделать мультиклассовость, так же, как и с пакетом?

2) Roots - корнеплоды!

3) \begin{document} - \end{document} : видимо, глобальное окружение, аналог int main() ?
Пробел расценивается как окончание команды, значит, \begin {document} - синтаксическая ошибка?

4) [] - используются как параметры ввода( часть синтаксиса), и как обычный текст. Не будет ли ошибок или недопониманий транслятором?

5) Проблема с русскими символами:
с. 259: ! Package babel Error: You haven't specified a language option. - log-файл
See the inputenc package documentation for explanation.

6) install-tl --version : шо за знаки такие, тире-тире, объясните!

7) Почему у меня реализация TexLive установлена сразу и в /usr/share/texlive/... и в личное пространство: /Dima/TexLive/... ?

8) Сделать выходной текст со своим шрифтом, как? 

9) Как подсчитать количество букв/символов в созданном тексте?

10) Файл шрифта пишется для всех языков?

11) Ошибка: \endcsname ?

12) с.46 Почему в Tex'е пункт = 0,315 мм. А как же единые типографские стандарты?

13) Как набрать абсолютно любой символ, используя его код в юникоде?

14) Неужели все размеры шрифтов ограничиваются 10-12 пт и их производными? Нельзя сделать, значит, гигантский шрифт?

15) Вопрос с интервалом в абзацах с изменённым шрифтом. Странности?

16) Конфликт команд: \textbf{\textmd slovo} - окрашивает только 1 букву в цвет внутренней команды.

\textbf{\textmd\textmd slovo} - окраска полностью в цвет внешней команды.

17) с. 49: как учесть все лигатуры сразу в документе?

18) Какая-то чётность/нечётность команды: \textbf{\textit \textit \textit \textit \textit slovo} - первая буква курсивом, 

\textbf{\textit \textit \textit \textit slovo} - никакого курсива.

\textbf{\textit \textit \textit slovo} - опять курсив.

19) Неполадки с цветом: почему в .dvi цвет (фон страницы) не отображается, а в .pdf да?

20) Команда \pagecolor работает только на весь документ. Как сделать разный цвет на разных страницах?

30) Как создать свой колонтитул в tex'е?

31) Плавающие объекты, выведены, что это значит? с.71

32) Как в tex'e сделать английские рубрики и русский текст, не отключая кириллицу и хитроумно не манипулируя языками? Специальные команды?

33) Как сделать секционирование из 4 чисел? Больше?

34) с.84: Не работают команды \pagestyle и \thispagestyle!

35) c.79: Мысль по поводу двойной компиляции при создании оглавления (содержания). Возможно, дабы соблюсти стройность системы, а также её платформенную независимость (что выражается в существовании многих собственных форматов и расширений - .toc, .aux, .tex, .bbl, и т. д.), после первой компиляции в командную систему, привязанную к текущему докуменуту, создаётся фиктивная команда, которая говорит нам системе: добавить оглавление, учесть/не учесть такие-то заголовки и т. д. Суть в фиктивной команде, я же её не писал напрямую, она результат сбора компиляции. Затем ряд команд (вместе с фиктивной) упаковывается окончательно, вторая компиляция призвана просто отобразить строго всё по плану и полученной структуре.

36) \footnote[в42] - некорректный вывод, сноска под номером 226. С чем-то это связано, кодировка данного символа?

37) Очень личные и подробные комментарии транслятора к ошибкам и предупреждениям. Такое ощущение, что нам по почте переслали полусерьёзное-полудурашливое объяснение недоразумения. Как это осознать? Это плохо, или наоборот, высшая планка качества?

Пример: I suspect you've forgotten a `}', causing me to apply this
control sequence to too much text. How can we recover?
My plan is to forget the whole thing and hope for the best.

#Musescore

1) Нет Selection Filter? Где значок копирайта? (С)? Ширина тактов?

2) Score - партитура!

#Язык запросов Yandex:

1) Зачем они сделали идентичные операторы "-" "~~"?
