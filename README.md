# apcminiremote_ma2

NodeJS version 14.17: https://nodejs.org/dist/v14.17.0/node-v14.17.0-x64.msi

//config 

wing = 1;   //set wing 1, 2 or 3 mode

pageselect = 1;   //set page select mode - 0-off, 1-only exec buttons(5), 2-exec buttons and faders together(5)

midi_in = 'APC MINI';     //set correct midi in device name

midi_out = 'APC MINI';    //set correct midi out device name 


mk2 version and mk2 color


----------------

//config 

wing = 1;   //set wing 1 or 2 (or 3)

pageselect = 1;   //set page select mode - 0-off, 1-only exec buttons(5), 2-exec buttons and faders together(5)

midi_in = 'APC mini mk2';     //set correct midi in device name

midi_out = 'APC mini mk2';    //set correct midi out device name

brightness = 6;     //led brightness 0-6

darkmode = 0;   //new color mode 1 - ON , 0 - OFF

autocolor = 1;  //Executors color from apperance - 0 = off, 1 = ON

blink = 0;      //no color Executor blink 1=on, 0=off 

--------------------------------

WING MODES


WING = 1

Executors (3 x 5 view)

101 - 108

116 - 123

131 - 138

...

176 - 183

faders

1 - 8 + grand master fader

--------------------------------------------------------------------------------------

WING = 2

Ececutors (3 x 5 view)

108 - 115

123 - 130

139 - 145

...

183 - 190

faders

8 - 15 + speed master 1 + lern (shift button)

--------------------------------------------------------------------------------------

WING = 3

Executors ( wing 1 - 2 x 5 view)

131 - 140

141 - 150

151 - 160

...

191 - 190

faders

16 - 23 + grand master fader


-------------------------------


Console connection:

var client = new W3CWebSocket('ws://localhost:80/');

-> change localhost:80 to console IP Address

-------------------------------- 


AKAI APC CONTROL


Executors ( 6 x 8 )

Color Yellow - if programed

Color Green - if run

-

Faders ( 3 x 8 )

Color RED if programed

Color Green if run

-

SCENE LAUNCH BUTTONS ON RIGHT SIDE

Select PAGE 1-8

-

last fader - Grand Master

-----------------------------------------------------------------------

Tips

Turn off autofix option for Action Buttons - use command

Assign Executor 101 Thru 190 /Autofix = "Off"

