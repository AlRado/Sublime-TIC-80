# Sublime-TIC-80
package for Sublime Text 3 for TIC-80 game developers

Description
===========

'Sublime TIC-80' is a package for [Sublime Text 3](http://www.sublimetext.com) for TIC-80 game developers. Its based on [BetterLua](https://github.com/Xuerian/Sublime-BetterLua) and [Moonscripty](https://github.com/rorydriscoll/LuaSublime).
The package highlights and auto-completes the functions of the TIC-80 API, the standard libraries connected to it and Lua/MoonScript syntax. Works either for Lua and for MoonScript.
Also it allows you to build game and run it by the TIC-80 fantasy game console.
TIC-80 ver.0.22.0 is supported.

Installation
============

These files should be placed into the 'TIC-80' package directory. 
For Windows this directory is:

C:\\Users\\[USERNAME]\\AppData\\Roaming\\Sublime Text 3\\Packages\\TIC-80

(Optionally) Disable built-in Lua package to prevent conflicts - remove file 'Lua.sublime-package' from C:\\Program Files\\Sublime Text 3\\Packages\\


Syntax highlighting 
-------------------
Command Palette: 
Set Syntax: TIC-80 lua 
Set Syntax: TIC-80 moon 


Completions
-----------
Autocomplete by pressing TAB after writing the function name.
See all snippets in window Tools -> Snippets. In order to see only API functions write here 'TIC-80 API', to see 'string' library functions write here 'string' and so on.


Build game for TIC-80
---------------------
Edit TIC-80.sublime-build before launch building.
By default, path to TIC-80 is 

C:\\Program Files\\TIC-80\\tic_0.21.0\\tic.exe

To build your game select build system in window Tools -> Build System -> TIC-80


Описание
========

'Sublime TIC-80' это пакет для [Sublime Text 3](http://www.sublimetext.com) предназначенный для разработчиков игр под TIC-80. Он основан на пакетах [BetterLua](https://github.com/Xuerian/Sublime-BetterLua) и [Moonscripty](https://github.com/rorydriscoll/LuaSublime).
Пакет подсвечивает и автодополняет функции API TIC-80 и подключенные к нему стандартные библиотеки. Работает либо для Lua либо для MoonScript. 
Также позволяет создавать билд игры и запускать её в виртуальной игровой консоли TIC-80.
Поддерживается TIC-80 ver.0.22.0.


Установка
=========

Эти файлы должны быть размещены в директории пакета 'TIC-80'.
Для Windows, эта директория располагается тут:

C:\\Users\\[USERNAME]\\AppData\\Roaming\\Sublime Text 3\\Packages\\TIC-80

(Опционально) Отключите встроенный пакет Lua для предотвращения конфликтов - перенесите файл 'Lua.sublime-package' из C:\\Program Files\\Sublime Text 3\\Packages\\


Подсветка синтаксиса
--------------------
Command Palette: 
Set Syntax: TIC-80 lua 
Set Syntax: TIC-80 moon 


Автодополнение
--------------
Автодополняется по нажатию TAB после написания имени функции.
Смотрите все сниппеты в окне Tools -> Snippets. Чтобы увидеть только функции API, напишите здесь 'TIC-80 API', чтобы увидеть библиотечные функции 'string', напишите здесь 'string', и так далее


Создание билда игры для TIC-80
------------------------------
Отредактируйте файл TIC-80.sublime-build перед запуском создания билда.
По умолчанию путь к TIC-80:

C:\\Program Files\\TIC-80\\tic_0.21.0\\tic.exe
