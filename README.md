## GitBash

1. Посмотреть где я.
   * команда `pwd`.
2. Создать папку.
   * команда `mkdir group_27`.
3. Зайти в папку.
   * команда `cd group_27`.
5. Создать 3 папки.
   * команда `mkdir -p {F_1,F_2,F_3}`.
7. Зайти в любоую папку.
   * команда `cd F_1`.
9. Создать 5 файлов (3 txt, 2 json).
   * команда `touch name{1,2,3}.txt name{1,2}.json`.
11. Создать 3 папки.
    * команда `mkdir folder{1,2,3}`.
13. Вывести список содержимого папки.
    * команда `ls -1`.
15. Открыть любой txt файл.
    * команда `vim name3.txt`.
17. Написать туда что-нибудь, любой текст.
    * нажать кнопку `i`.
    * вводим текст `The United Kingdom is an advanced European island country. 
It is surrounded by three bodies of water: the North Sea, in the eastern part, the English Channel in the southern part, and the Atlantic Ocean in the west. 
The country consists of England, Scotland, Wales, and Northern Ireland. The term “United Kingdom” is often confused with the term “Great Britain”, which is the name of the island, but not the state. 
Many smaller islands and adjacent territories form an integral part of this country, as well as the area of Northern Ireland in the northwest. 
The total area of the country is 242,500 sq. km. The population is over 67 million people, according to the 2020 statistical data.
`.
19. Сохранить и выйти.
    * нажать кнопку, чтобы выйти из режима редактирования `esc`.
    * ввести команду `:wq`.
21. Выйти из папки на уровень выше.
    * ввести команду `cd ..`.
23. Переместить любые 2 файла, которые вы создали, в любую другую папку.
    * ввести команду `mv F_1/{name3.txt,name1.json} F_1/folder1`.
25. Скопировать любые 2 файла, которые вы создали, в любую другую папку.
    * ввести команду `cp F_1/{name1.txt,name2.json} F_1/folder2`.
27. Найти файл по имени.
    * ввести команду `find folder1 -name "name1*"`.
29. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает.
    * ввести команду `find folder1 -name "name1*"`.
31. Вывести несколько первых строк из текстового файла.
32. Вывести несколько последних строк из текстового файла.
33. Просмотреть содержимое длинного файла (команда less) изучите как она работает.
34. Вывести дату и время
