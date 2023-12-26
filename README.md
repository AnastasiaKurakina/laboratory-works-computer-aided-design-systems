# laboratory-works-computer-aided-design-systems
лабораторные работы по учебной дисциплине "автоматизация проектирования" студентки уч. гр. М3О-309Б-21 Куракиной А.С.
задание к л/р:
Завести репозиторий в Git (gitlab)
Добавить файлы в репозиторий (README - с описанием проекта, имя автора, номер группы + любая программа на C/C++/Python/SV, работу которой легко проверить)
Создать ветку с обновлением (добавить функциональность в файл с исходным кодом, и в README описание изменения)
Переключится в исходную ветку
Обновить любой файл там
Влить изменение из первой ветки во вторую (при возникновении конфликта - решить конфликт и сделать коммит)
Влить итоговый результат в исходную ветку.
********
Разработать и протестировать APB мастер (несинтезируемый) и, по необходимости, базовый APB слейв.

Для мастера надо разработать функции записи и чтения:

void apb_write (logic [31:0] inp_addr, logic [31:0] inp_data);

logic [31:0] apb_read (logic [31:0] inp_addr);
********
Слейв должен поддерживать обмен и выдавать через display сообщения о совершаемых операциях.
********
Выполнить следующие операции:

запись по адресу 0x0 значения <ваш номер в списке группы>

запись по адресу 0x4 значения <дата в формате дд.мм.гггг>

запись по адресу 0x8 значения <первые 4 буквы вашей фамилии в формате ASCII>

запись по адресу 0xC значения <первые 4 буквы вашего имени в формате ASCII>
*********

Примечание:

задание 8-9 должны выполняться с использованием GIT. Все серьезные изменения (добавление нового модуля/новой функции/новой функциональности) должны оформляться отдельными коммитами.

Минимум должно получиться не менее 4 коммитов (больше можно).

    добавление файла мастера

    добавление файла слейва

    добавление модулья верхнего уровня

    финальная версия с тегом(!)

В репозитории должны находится ТОЛЬКО исходные файлы и файлы скриптов для запуска + файл README.

В отчете по ЛР приложить ссылку на репозиторий, показать историю проекта и вывод git log .
