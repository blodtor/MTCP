
mTCP Source Code Readme
2022-07-01 Version

Home page: http://www.brutman.com/mTCP/mTCP.html


Welcome to the mTCP source code!

mTCP documentation has moved to the developers.pdf file.  Topics include
the directory structure, what compiler to use, architecture and design
notes, and miscellaneous notes for programming under DOS.

Note: HTTPServ source code is not provided at this time.  It's overly
complex and I am not terribly proud of it.  Look for a smaller,
slimmer version in the future.



Enjoy!

Mike
mbbrutman@gmail.com
-----------------------------------------------------------------------------

Super Turbo NET Pac-Man v1.3 
2022-09-03 Version

реализация Pac-Man для DOS (IBM PC XT Intel 8088) и GNU/Linux для 2х игроков
использует в DOS mTCP для создания сетевого соединения при игре по сети
исходный код тут: APPS\PACMAN\pacman.cpp

Описание игры:
1 игрок управляет Pac-Man за которым гоняется 1 призрак красного цвета, 
в случае если призрак догонит Pac-Man - игра закончится.
в случае если Pac-Man или Pac-Girl съедят большую зеленую точку, призрак станет 
фиолетового цыета и начнет убегать от Pac-Man т.к. теперь его самого можно съесть
2 игрок управляет Pac-Girl. Она помогает собирать точки на уровне при этом ни Pac-Man ни 
призрак не могут съесть Pac-Girl а она их (бессмертная) 
Игра закончится победой если гроки смогут сбрать всю еду (маленькие и большие точки) на уровне
В доме призраков через некоторое время появляется вишня - за нее просто дают очки 
чтоб выиграть есть не обязательно ее!

PACMAN\pacman.exe - DOS приложение работающее в графическом режиме 320 x 200 16 цветов

Примеры запуска:
pacman.exe - одиночная игра или 2 игроками на одной клавиатуре.
	управление стрелочками - игра за Pac-Man (1 игрок)	
	управление wasd - игра за Pac-Girl (2 игрок) 
pacman.exe 7777 - запуск сервера, ожидающего подключения 2 го игрока на 7777 порт (порт можно любой не занятый указывать) 
	управление стрелочками - игра за Pac-Man (1 игрок)	
pacman.exe 192.168.1.101 7777 - запуск клиента, подключающегося к запущенному серверу на хосте  192.168.1.101 и 7777 порту
	управление стрелочками - игра за Pac-Girl (2 игрок)	

PACMAN\pacman - Linux приложение работающее в консольном режиме (собронное в Ubuntu 20.04)

Примеры запуска:
pacman - одиночная игра или 2 игроками на одной клавиатуре.
	управление стрелочками - игра за Pac-Man (1 игрок)	
	управление wasd - игра за Pac-Girl (2 игрок) 
pacman 7777 - запуск сервера, ожидающего подключения 2 го игрока на 7777 порт (порт можно любой не занятый указывать) 
	управление стрелочками - игра за Pac-Man (1 игрок)	
pacman 192.168.1.101 7777 - запуск клиента, подключающегося к запущенному серверу на хосте  192.168.1.101 и 7777 порту
	управление стрелочками - игра за Pac-Girl (2 игрок)	

BlodTor
blodtor@gmail.com