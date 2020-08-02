+++
title = "Keyboard"
author = ["Jacob Chvatal"]
lastmod = 2020-08-01T23:02:16-07:00
slug = "keyboard"
draft = false
+++

Research on keyboards and keyboard configurations.


## Work {#work}

QMK
<https://github.com/pierrechevalier83/ferris> one hand kb
<https://github.com/AlexBravo/Twiddler> one hand chording kb
<https://github.com/ItayGarin/ktrl> keyboard programming daemon


## ETC {#etc}


### what do I want my keyboard to do? {#what-do-i-want-my-keyboard-to-do}

-   type, well
-   preserve some similarity to my laptop keyboard
-   make it easy to do the things i can do in i3 on laptop already
-   midi layer to play notes and make music !!

poker : mapping to colemak <http://thedarnedestthing.com/poker%202>


### qmk configuration tips and links {#qmk-configuration-tips-and-links}

<https://thomasbaart.nl/2018/12/20/qmk-basics-leader-key/>
 -- defining sequences with which you can trigger keypresses and functions!
 this uses lead -> cut instead of having to hold the whole sequence all at once


### practicing {#practicing}

[keyboard practice site](https://www.keybr.com/)
[on the proper planck writing style](https://www.youtube.com/watch?v=4Ej%5F3NKA3pk&app=desktop)


### keycaps {#keycaps}

<https://ramaworks.store/products/grid-set-a?variant=16185116000299> -- low
profile with a center thing, injection molded


### etc {#etc}

<https://www.keebwerk.com/nano-slider/> --cool mini keyboard thing that includes a
slider!

<https://github.com/tomsaleeba/qmk%5Ffirmware/blob/master/users/tomsaleeba/tom.c#L157>
-- cool key combination ideas... though maybe these should be done in
software? unclear.
<https://blog.splitkb.com/how-to-work-with-small-keyboards> -- qmk layering tips!
make use of combos for cooler keyboard motions.
<https://macintacos.github.io/macinplanck-configuration> -- someone's strict
planck configuration


### alternative keyboard layouts {#alternative-keyboard-layouts}

<https://www.reddit.com/r/olkb/comments/6feemo/creating%5Fa%5Flayer%5Ffor%5Fvimhjkl%5Fwhen%5Fusing%5Fan/>
<https://colemakmods.github.io/mod-dh/> -- alternative
<https://github.com/macintacos/dotfiles/blob/master/keebs/macinplanck-ez/macinplanck-keymap.pdf>
-- someone's idea of a cool keyboard layout


### rough ideas {#rough-ideas}

greek letters behind a hidden layer for fast math typing

-   on this layer remap shift so that it opens capital greek letter
    reevaluate how i use modifier keys and where i put my thumbs for ease of access

what else do i type frequently?
what is the fastest way to lay out the numpad to enable quick access?
what function keys or macros would be useful to me?
emojis?? on my keyboard??
  introduce leader keys and macros to spit out some keyboard shortcuts,
music, or important information
explicitly document this somewhere
dont be afraid to draw out specific layout!!
  <https://forum.colemak.com/topic/2206-planck>
this is very good thread with sdothum keyboard layou
  <http://thedarnedestthing.com/colophon> -- god keyboard configuration layout and blog
i love the Major Mono Display font! try to make some web dev project with thi
  <http://mkweb.bcgsc.ca/carpalx/> -- unique perspective on designing and creating
a keyboard to prevent carpal tunnel problems from occuring with a keyboard
configuration and layout
obviously best action to take is planck or split keyboard, but the next action
to take is changing the keyboard layout to radically change the way the
fingers move as we type!
do not place constraint on how many keys are relocated
places on this site layout the q\*\*lw\* layouts for optimizing for various things,
one keeps zxcv in place for greater effeffectiveness. consider using one of
these as opposed to colemak or somethign for better effectivenes
  in geneeral: find what isnt working and optimiz
potential ideas- macros for different latex expressions(it is possible that org
mode already offers this)it may be better to just use org mode for latex and
shortcut the org mode expressionsthis should be some 'math mode' laye- midi
control layer- offers potential for drum kit as well as for a piano roll of some
sort- perhaps dual buttons for tweaking knobs up and down- mappings similar to
launchpad to programs such as abletonhttps://github.com/theniceboy/nviif i use
colemak i will probably have to make some changes to other keybindings to
reflect thicurrent are proper for qwerty but these ssame binds will not make
sense in other placesfrom planck repos- ajp10304hold tab for shifthold enter for
shifthold space for some function laye
macros:

-   backspace + control
-   delete with control
-   layer specifically for navigation and typing brackets
-   layer with copy, paste, duplicate, other things functionality

58 - sdothum
colemak-dh
shift tab key overlays
number and symbol function key layer
layer with hex numbers
layer with navigation and keypad
autocompletion of key pairs
extensive use of tap keys for different layout
67 - am
media keys
both qwerty and colemak
number and reversed number pads for both hands
touchccursor layEr  ?? look into this
mouse layer
74 - voodagod: bone2planck
ergonomic placement for coding for things on second layer (m1)
navigation and number blocks in convenient and intuitive place
function and media keys on separate layer from navigation keys 2 layers that swap funvtion and media ke    ys as well as switched navigation and number blocks
4 mod keys, 2 on either side of the spacebar
80 - cbbrowne
keypad layer has cool macros:

-   automatic type out of name with leaders
-   random number generator spits out number

hold enter for shift
helping with tmux:

-   may be helpful to add tmux layer
-   this would have macros specific to the navigation of tmux
-   kc lead to find key combos not concurrent

jeebak keymap with good ideasL:

-   number layer has numbers in several places
-   touchcursor allows for cursor layer on home keys

jeremy-dev keymap also cool

-   shift hands outwards, special keys in center
-   symbol layer has compound keys for c operators
-   this would have macros specific to the navigation of tmux
-   kc lead to find key combos not concurrent

jeebak keymap with good ideasL:

-   number layer has numbers in several places
-   touchcursor allows for cursor layer on home keys

jeremy-dev keymap also cool

-   shift hands outwards, special keys in center
-   symbol layer has compound keys for c operators96 - corvec
    redundancy for common keys so that they are easily accessible

this is especially true for keys that can be out of the way
autoshift but also defined shift keys as autoshift is slow
movement is hjkl or hnei depending on the keymap
arrows mimicked by home, pgdown, pgup, and end on the lower row
media keys same location as Arrow keys
toggle layers minimized so that keyboard state is predictable
shift toggle? deactivate automaticall

-   dcompact

stateless typing
minimize mouse usage
has Plover integration for stenotypi

-   sdothum

colemak dh with shift tabn key overlays
number, symbol, function key layers
hex keypad layer
navigation keypad layer
dynamic macro layer
extensive use of tap keys

-   hvpkod

swedish keys on main layer using tap dance (what is tap dance

-   impossible by UnderSampled

main objective:

-   move most used punctuation to the thumbs
-   removing s middle column??
-   other space gains conbine keys only chorded with non symbol keys as well as function layer asnternati    ves
-   qwerty layer seems to be entirely normal

stenoigraphy: moves number low below the regular keys,providing comfortable placement for the thumb key    s
switch between layouts and change other keyboard settings with adjustment lay

-   jeremy-dev

programmer who avoids rsi so they want to avoid stuff
makes heavy use of momentary layer toggling
momentary toggles, hold single mods like backspace, space, etc. for better functionality
symbol layer keys accessible via the thum

-   jeremy-dev

programmer who avoids rsi so they want to avoid stuff
makes heavy use of momentary layer toggling
momentary toggles, hold single mods like backspace, space, etc. for better functionality
symbol layer keys accessible via the thum

-   laeleth

standard querty layout for main page
lower layer places all numbers on a single hand
raise layer prioritizes parens over all else
numpad layer for single hand numpad: is this a good ide

-   matrixman

wanted pinkeys to have a break or something
index fingers and palm presses do a lot more
planck mobile, ergodox at home, want to minimize difficulty of switching between the t

-   yttyx

base layer uses balance twelve layout??
plover layer uses the same home position as the base layer
link ref:: mathmaticalmulticore.wordpress.com/the-keyboard-layout-proje

-   steno

stenography keymap for the keyboard
set plover to TX bolt, select com port that represents keyboa

-   snowkuma

colemak planck layout
influenced by sdothum and blog
allows for minimisation of key usage to set and having hands in comfortable position
colemak base layer
symbol cursor nav layer
notably blocks out two middle layers for unknown reason
has regex layer jsut on right hand for good expressions
magnet shortcuts?
thumb shortcut layer
function layer with lots of keys
mouse layer that allows for easy navigation (what does the gui bbutton do

-   smt

has mod-tap keys re: jackhumbert qmk firmware fun with modifier keys article
using left shift as mod tap for escape?? this seems weird man
tab is also the hyper key when held down
backtick is in the lower left corner, used as the tmux prefix key
group open paren and closed paren togeth

-   smittey

focused on coding and utilizes home row for common symbols
space is also function key, and leads to arrow key navigation scre

-   sean

typematrix dvorak keyboard with escape, tab, enter and backspace in the middle rather than on outside
middle row functions hold most of the functionality
the adjust layer has one shortcut copy, paste, numpad, dvorak etc layer acces

-   samuel

pretty mode organized for dvorak
has tap keys configured with all of the keys held above as alternate layer

-   all keys shoukld have alt tap functionality to provide better access to th
    function and macro layer for one shot things

python layer as well??
good layout of code for keym

-   priyadi planck layout

emoji layer ! cursor and nav cluster available on the home row
number layer supports hex input somehow
left and right side modifier keys
faux clickey?? i think this means it makes sounds when the keypresses register
which is stup

-   pascamnothing special - mostly default - but another good reference for how to
    place keys on the keyboa

    -   oeywnorwegian grid layoleader keys, tap dancing and

    aud

    -   piemod by choromansoffers support ofr ortho, i3wm and programming symbono

    documentation though. Sa

    -   piemod by choromanskiers support ofr ortho, i3wm and

    programming symbolsno documentation though. Sadtakeawaymake all hold keys also
    tap keys with a different functionalitlayers fo- navigation ( should have
    dedicated copy, paste, etc functionality for ease of navigation and moving tex
    t aroun- programmer buttons - common progrmmer symbols to type as well as
    macros to help with progrma typi- typing greek lette- latex symbols ( could be
    combined with the greek letter thing) this is largely an alternative note taki
    ng mode to be used in math courses or something, possibly in conjunction with
    org mode. do soem research     on taking literate notes with latex and get
    back to this. for now just do the greek letters?? lots of coo    l programming
    can be done here to enter and exit contextual programming modes inside
    different scopes for     entering and exiting them by remembering scopes as
    well as previous keys, or typing out entire commonly     used latex symbols
    concretely through the keyboa- commonly used phrases - this shouldn't be a
    layer so much as a series of macros defined by leader keys     that can be
    accessed via normal tyoping layer, and should include email, name etc. could
    also create pass    word buffer in the firmware to write, read copy and paste
    to but ideally some external program should han    dle th- some toggle layer
    for a midi controller or music making mode!!! only do this wehn you get back
    into mus    ic production or find some way to do something like thend goal:
    completely navigate computer without any usage of the keyboard using
    conjunction of software an    d hardwar


### etc {#etc}

<https://vlukash.com/2019/01/14/corne-crkbd-keyboard-build/>
these are good instructions for the corne keyboard
<https://gist.github.com/Monroe88/0f7aa02156af6ae2a0e728852dcbfc90>
retroarch keyboard mapping template
<https://www.reddit.com/r/MechanicalKeyboards/comments/5ca2vh/interested%5Fin%5Fmaking%5Fa%5Fscientific%5Fkeyboard%5Fbut%5Fam/>
making a scientific keyboard
<https://www.reddit.com/r/olkb/comments/aozex6/want%5Fto%5Fadd%5Fa%5Flayer%5Ffor%5Fthe%5Fgreek%5Falphabet%5Fand/eg5nwzh/>
greek layers as well as qmk macros
<https://blog.splitkb.com/how-to-work-with-small-keyboards>


### switches {#switches}

[next ones to try](https://novelkeys.xyz/products/kailh-speed-switches)
[configuring leds](https://github.com/RustyJonez/OLED-ART-tinkering)


### steno {#steno}

<https://didoesdigital.com/blog/build-your-own-steno-keyboard-its-easier-than-you-think/>
<https://github.com/openstenoproject/plover/wiki/Learning-Stenography>
<https://store.steampowered.com/app/449000/Steno%5FArcade/>


### research on layouts {#research-on-layouts}

<http://mtgap.bilfo.com/keyboard.html>
<https://en.m.wikipedia.org/wiki/FrogPad>
<https://www.reddit.com/r/KeyboardLayouts/comments/feikcf/seelpy%5F1%5Fergolinear/>
<https://www.keyboard-design.com/letterlayout.html?layout=essie-2.en.matrix>
<https://www.keyboard-design.com/letterlayout.html?layout=seelpy-1-22.en.ergolinear>
<https://www.keyboard-design.com/best-layouts.html>
<https://www.keyboard-design.com/layouts/ergo/60/seelpy-1-ergolinear.html>
<https://www.reddit.com/r/KeyboardLayouts/comments/ffvuxh/soul%5Fis%5Fa%5Fcolemaklike%5Flayout%5Fdesigned%5Ffor%5Fmore/>
<https://ieants.cc/code/keyboard/beakl/>
<https://deskthority.net/wiki/BEAKL>
<https://mathematicalmulticore.wordpress.com/category/keyboards/>
<https://www.reddit.com/r/KeyboardLayouts/comments/gx1wxa/ergo%5Flayouts%5Fcomparison/>
<https://mathematicalmulticore.wordpress.com/category/keyboards/>
<https://www.reddit.com/r/KeyboardLayouts/comments/fevb94/a%5Fbrief%5Fsummary%5Fof%5Falternative%5Fkeyboard%5Flayout/>
<https://www.reddit.com/r/ErgoDoxEZ/comments/gsvpug/layout%5Fof%5Fthe%5Fmonth%5Fbeakl%5F15/>
<https://colemakmods.github.io/ergonomic-mods/extend.html>

<https://www.reddit.com/r/olkb/comments/h00a8b/i%5Fmade%5Fan%5Foled%5Fanimation%5Fof%5Fbongo%5Fcat%5Fthat/>
hooly shit

<https://www.reddit.com/r/olkb/comments/gwy4zz/a%5Flittle%5Fquarantine%5Fproject/> --
top top to pdesign, very cool and modular!
<https://vlukash.com/2019/01/15/trackpad-in-keycap-corne-crkbd-keyboard/#more-544>
trackpad in a keycap!

general plan:

-   use beakl layout for thumb clusters
-   use the modified colemak variant for the qwerty keys
-   think hard about how to arrange the alternate layers

[extend layer](http://colemakmods.github.io/ergonomic-mods/extend.html)
<https://github.com/abstracthat/dactyl-manuform>
<https://ramaworks.store/products/grid-set-b?variant=31922049318990> neat
keycaps

[get elite c, sockets](https://docs.splitkb.com/hc/en-us/articles/360011091759)

[kb trackpad](https://vlukash.com/2019/01/15/trackpad-in-keycap-corne-crkbd-keyboard/#more-544)


### IDEA: configuration has two types of keymappings. {#idea-configuration-has-two-types-of-keymappings-dot}

one is relative to the
location on the keyboard, while another is relative to the letter.  i like
mixing both of these. there should be some system for allowing me to easily
do the former?