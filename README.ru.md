<h2> Vious - виртуальный помощник для изучения английского языка </h2>

Vious это приложение предназначенное для помощи людям в изучении английского языка.

<h3> Краткое описание возможностей. </h3>

Вы можете добавлять в Vious те слова - которые хотите изучить, программа будет хранить их у себя в памяти ( локально ) и использовать для дальнейшей работы.

Есть режим обучения - для изучения добавленных слов, и для повторения раннее выученных. В режим обучения добавлен специальный алгоритм для более эффективного изучения.

Главная фишка Vious - в том что она упрощает и способствует изучению Английского языка по видео и аудио материалам с субтитрами. Например по фильмам, сериалам, мультфильмам и т.д. . ( подробнее в расширенном описании )

<h3> Новости. </h3>

.......... Vious-2.0 : Первая версия Vious в консольном режиме.

26.01.2019 Vious-3.0 : добавлена возможность онлайн перевода с использованием https://translate.yandex.ru/

<h3> В Vious предусмотрены различные команды для работы : </h3>
1) #exit - команда предназначена для выхода из программы
2) #stats - выводит информацию про общее количество слов, количество изученных слов, количество не изученных слов
3) #parse - берёт файл с субтитрами, сканирует файл - записывая в результирующий файл отдельные слова.
4) #compress - сжимает файл со словами - удаляя похожие слова, и сохраняет в результирующий файл - только уникальные слова.
5) #new_from_file - берёт файл с новыми словами ( формата "сначала - количество слов. затем - все слова на английском. в конце - перевод слов на русский" ) и добавляет те слова - которые нет у Vious в базе. Пример файла https://github.com/RooBarsic/My_Projects/blob/master/Vious/Vious-2.0/new_words.txt
6) #new - для добавление новых слов. Сначала вводите количество добавляемых слов, затем сами слова с переводом.
7) #Alisa_learn - добавление новых слов, при этом вы сами не переводите слова. Слова переводятся с использованием https://translate.yandex.ru/ ( Переведено сервисом «Яндекс.Переводчик» http://translate.yandex.ru/. ) , а вы подтверждаете - хотите ли вы добавить такой перевод. Эта команда добавлена в версию Vious-3.0.
8) #learn - переход в режим обучения. В этом режиме есть две группы слов - изученные и не изученные.
В режиме обучения есть три команды :

8.1) 1 - знаю перевод слова ( если вы хорошо помните перевод, то это слово перейдёт в группу изученных )

8.2) 2 - не знаю перевод слова ( если вы плохо помните перевод, то это слово перейдёт в группу не изученных )

8.3) 3 - завершить тренировку с этой группой слов

<h3> Комментарии автора : </h3>
Приложение находится на стадии разработки.

26.01.2019 В данный момент приложение работает в консольном режиме с поддержкой вышеупомянутых команд для работы в последней версии.

Ожидается версия с графическим интерфейсом и улучшение алгоритмов изучение.

<h3> Советы по использованию : </h3>
1)Используйте частые и короткие тренировки, например 15-20 минут утром и ночью ( а также в другое свободное время ).
2) Добавляйте субтитры фильмов - которые вы хотите просмотреть.

<h3> Технологии : </h3>
Программа написана на языке программирования Java. Использует yandex.translate API, и работу с файлами. 
Переведено сервисом «Яндекс.Переводчик» http://translate.yandex.ru/.
