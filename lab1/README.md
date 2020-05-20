## Лабораторная работа 1  
## Пакин Андрей Сергеевич ББСО-01-18  

1 Воспользовался cat для отображения файла  
ls для отображения содержимого каталога  
ZGFpejZhaFJhZVNhZXhhaWJ1YWYK  
 ![Картинка](screens/screens/1.jpg)

2 Использовал cat ./* - для отображения всей информации  
dGhlaWxpM2FoWm9odGFpM2VldzMK  
 ![Картинка](screens/screens/2.jpg)

3 Сначала ls, т.к. кроме листа нет команд, прочитал построчно нужный файл в директории  
whileread $LINE; doecho $LINE; done<./-diary.txt-;  
Y284ZWlxdXVlMmllTDNpZXBoNWUK  
 ![Картинка](screens/screens/3.jpg)

14 cd перемещение по каталогам  
cd .. - на позицию вверх  
d2FodmFoMWFlV2FpYmVlaG9vMmIK  
 ![Картинка](screens/screens/14.jpg)

15 Чтобы понять где мы находимы – использовалpwd (presentworkingdirectory - текущий рабочий каталог)  
TWVlMXdvaDJ6YWVoZWoyamllNm8K  
 ![Картинка](screens/screens/15.jpg)

16 id - показывает информацию о user'е  
ZXVsb29naG91MFBob2g4T2hkYWkK  
 ![Картинка](screens/screens/16.jpg)

17 Так как у нас скрытый файл, то нужно делать через:  
ls -a который выводит скрытые файлы  
bmVlNm1lMEhhaU11M2thaGVpNmEK  
 
![Картинка](screens/screens/17.jpg)









18 mandiary - чтобы получить руководство по diaryв flagпароль  
Y2hpZWNoM2VpRzRJZWtlaXNlbGUK  
 
![Картинка](screens/screens/18.jpg)
19 mkdir - создание директории  
mkdir -p - создание сразу нескольких вложенных  
cd - переходим в директории для создания следующей  
V2VpMGNvaHNoZWlxdWE0YWhnaG8K  
 ![Картинка](screens/screens/19.jpg)





20 rm -R (рекурсивное удаление директории и всех вложенных директорий)  
YW1pZWhpaW0yb2h5NW9vRjZlaXcK  
 ![Картинка](screens/screens/20.jpg)

21 rm *[0-9]*.txt  
rm *[a-z]*.png  
rm test-*.log (удаляем все не архивированные)  
(Используем rmдля удаления файлов); ls  
aWU0b29XdWxlaXBodXBpZWZveW8K  
 ![Картинка](screens/screens/21.2.jpg)  
 ![Картинка](screens/screens/21.2.jpg)
 

22 Цикл и touch для создания файла  
# i=1; while [ $i -lt 999 ];dotouch $i.txt;let i++;done;  
touch - создает файл, let i++ увеличивает счетчик на единицу. -lt == <;  
dXI2dXNhaDNvaFQxaWV2MGNobzgK  
 ![Картинка](screens/screens/22.1.jpg)
 ![Картинка](screens/screens/22.2.jpg)
 

23 Использовали ls / cd и mv (для перемещения и изменения названия каталога/файла)  
dmVlc2VpQzVBb2dlaXI1cmVlM2YK  
 ![Картинка](screens/screens/23.jpg)


24 Использовал ls, cd и cp -r (для копирования каталога)  
YWVnaG9venVvejd2b292OHNvaEwK  
 ![Картинка](screens/screens/24.jpg)  

25 Воспользовалсяls и cat  
dGhlZThhcXVpZUNpTGFpdGhlZTkK  
 ![Картинка](screens/screens/25.jpg)

26 Использовали less для отображения содержимого файла по страницам  
После использовали /SECOND, /THIRD для поиска флага  
WWVpc2gxYWlndXVrZWl5ZWloaWUK  
  ![Картинка](screens/screens/26.1.jpg)
 ![Картинка](screens/screens/26.2.jpg)
 ![Картинка](screens/screens/26.3.jpg)
 ![Картинка](screens/screens/26.4.jpg)

27 tail -f diary, выводим строки с конца (благодаря -fобновляется информации по мере появления новых строк в файле)  
dGVlMUtleThhUXVvaDFnZTFiaWkK  
![Картинка](screens/screens/27.1.jpg)
![Картинка](screens/screens/27.2.jpg)
 
28 cat<<EOF>diary  
<ввод текста без последней строки>  
EOF  
echo -n "11:32pm: Нассал под кресло. Еееееееее!" >>diary – для решени проблем непечатных знаков  
ZWV4b1g1WnVkMm9oZnVjYWhkdTMK    
29 Жмём стрелочку вверх для того чтобы узнать историю    
dmFvbmcwcGFlMWlodUJvaFppZWQK    
 ![Картинка](screens/screens/29.jpg)
