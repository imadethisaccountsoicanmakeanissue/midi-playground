# midi playground
bouncing square video, FOSS edition (and gamified)

## NOTICES

### for content creators:

please try to put the link to this repository in your youtube video descriptions if the youtube video features this software, that is all i request

### for developers:

***this code is licensed under GPL3, it is illegal to publicly distribute modified copies of this software without providing the source upon request!***

it is ok, however, to modify the code and not release the source if you are not releasing the modified version to the public.

## how to do custom songs?

see [docs/SONGS.md](https://github.com/quasar098/midi-playground/blob/master/docs/SONGS.md) for custom song tutorial

## development guide

this is how you set up the code to run it from source, rather than a bundled pyinstaller executable

download python from [here](https://python.org) specifically (3.9.1 should work). do not download from windows store. that version is really janky and doesn't work that well for more complex python programs with lots of dependencies

install requirements with `python3 -m pip install -r requirements.txt`

start program with `python3 main.py`

build command: `pyinstaller main.py --noconsole --onefile --clean --hidden-import glcontext`

## credits

see [docs/CREDITS.md](https://github.com/quasar098/midi-playground/blob/master/docs/CREDITS.md)

## contributors

- [quasar098](https://github.com/quasar098)
- [TheCodingCrafter](https://github.com/TheCodingCrafter) - Themes + QOL
- [PurpleJuiceBox](https://github.com/PurpleJuiceBox) - Reset to Default Button
- [sled45](https://github.com/sled45) - Mouse fix for high DPI displays
- [Times0](https://github.com/Times0) - dark_modern theme, Glowing, Colored pegs on bounce
- [Spring-Forever-with-me](https://github.com/Spring-Forever-with-me) - fix incorrect key name for screen resolution in the config
- [sj-dan](https://github.com/sj-dan) - opengl fix on mac os
- [cangerjun](https://github.com/cangerjun) - chinese translations

## translation guide

want to add translations for a different language? please create a github issue with the word "translations" in the title

if so, please add translations for as many of the texts (they are listed below) as you can

- "play"
- "config"
- "contribute"
- "open songs folder"
- "quit"
- "back"
- "midi-playground" text (this is the title of the software)
- the marquee on the title screen (the moving text that appears underneath the title on the main screen; see translations.py file for english example)
- "restart required"

if you have any questions on what any texts are supposed to mean, see translations.py for the english examples before you make a github issue

currently, this game supports english and chinese

also, we are only adding real languages (no pirate speak or upside-down language like minecraft)

## (old) todo list

see [docs/TODO.md](https://github.com/quasar098/midi-playground/blob/master/docs/TODO.md)
