# Руководство наблюдений с ПЗС-фотометром телескопа Цейсс-1000

## Завершение наблюдений

[Далее: заполнение электронного журнала](EJ.tex)

[Назад: фокусировка телескопа](Focus.md) 

[Вверх: на стартовую страницу](index.md)

В конце наблюдательной ночи нужно произвести ряд шагов для корректного завершения работы.

1. **Запарковать телескоп.** Для этого нужно выполнить следующую последовательность действий.

    1. Отправить телескоп и купол в парковочное положение. 
    Для этого нажать кнопку Parking вкладки Object в программе Zeiss GUI OBS.
    
    2. Когда купол остановится, закрыть забрало нажатием кнопки DomeDoors Close в веб-форме управления. 
    Обязательно  проверить, закрылось ли забрало до конца (что будет слышно по аудиоканалу, 
    видно по камере из подкупольного и отобразится в окошке состояния слева от кнопок управления забралом). 
    Если забрало закрылось не полностью, нажать кнопку закрытия забрала повторно.
    
    3. Закрыть крышки главного зеркала в той-же веб-форме.
    
    4. Проверить, выключен ли свет в подкупольном. Если нет, выключить кнопкой Light Off.
    
    5. Выключить питание купола кнопкой DomePower Off.
    
    6. Последовательно выключить большие круглые кнопки (правую и среднюю): SEW Power, Cabinets Power. 
    Должна остаться гореть зелёным только левая кнопка Tel. Tube Power. 
    
    7. Закрыть в браузере сессию веб-формы. 

2. **Закрыть программу Zeiss GUI OBS.**

3. **Создать лог (журнал) ночи.**
    1. Для этого нужно зайти в программе Dina System во вкладку Camera и выбрать пункт Create Log file.
    2. В открывшемся окне ввести имя файла в формате YYMMDD.
    3. В FAR или Total Commander найти этот файл и открыть его с помощью клавиши F4. 
    4. Отредактировать файл, добавив в поле Observers наблюдателей, а также дописав комментарии, если это требуется. 
    Сохранить файл (Ctrl + S или любым другим способом) и выйти из режима редактирования.

4. **Скопировать данные на машину tb.** 
Для этого в FAR или Total Commander нужно открыть FTP соединение с машиной tb.sao.ru, 
выйти в директорию /Data/archives.z1000/CCD/ и скопировать туда с диска E машины zobs директорию ночи со всеми файлами. 

5. **Закрыть соединение с zobs.** Можно просто закрыть окно соединения с удалённым рабочим столом.

6. **Завершить звонок в программе 3CX Phone**, закрыть окно этой программы и программы Sjphone.

7. **Заполнить бумажный журнал.**

8. **Заполнить [электронный журнал](EJ.tex).**

9. **Заблокировать сеанс пользователя на машине zrobs.**


[Далее: заполнение электронного журнала](EJ.tex)

[Назад: фокусировка телескопа](Focus.md) 

[Вверх: на стартовую страницу](index.md)