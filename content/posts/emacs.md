+++
title = "Emacs"
author = ["Jacob Chvatal"]
lastmod = 2020-08-01T22:09:32-07:00
slug = "emacs"
draft = false
+++

### Backlinks {#backlinks}

-   [acl2]({{< relref "acl2" >}})
-   [EXWM]({{< relref "exwm" >}})
-   [Vim]({{< relref "vim" >}})

Emacs is a fully-featured programming environment.

It's often (or most commonly) referred to as a text editor,
but this isn't the case. Other editors are designed to offer first-class
interfaces for configuring keyboard shortcuts, text configurations, etc.

However, emacslisp is structured not to be used as an editor configuration
with some additional logic capabilities, but rather as a fully-featured
programming language with proper language facilities.

Emacs is my desktop environment.[ EXWM]({{< relref "exwm" >}}) is my window manaager,
elfeed is my RSS reader, mu4e is my email client and so forth.
The one program that does not have a proper Emacs interface
is the web browser, so I use Firefox (and web apps) for most other tools.

This isn't to cause myself undue pain. It reduces context switching between
the keyboard shortcuts of many programs and their keybindings,
and allows time tracking, task tracking and information management
(all fractured, often difficult concepts) to be managed by [Org Mode]({{< relref "org_mode" >}}) entirely
within Emacs. This tight integration allows me to take notes and track
time without having to switch contexts to other programs with other
user interfaces.


## Tools {#tools}

[cloudmacs](https://github.com/karlicoss/cloudmacs) allows you to self-host your emacs configuration and access it in the browser.


## Configurations {#configurations}

<https://github.com/howardabrams/dot-files>
<https://github.com/jethrokuan/dots>
<https://github.com/codygman/hci> human programming interface in emacs
<https://github.com/Ambrevar/dotfiles>


## Community {#community}

<https://github.com/howardabrams/pdx-emacs-hackers>


## Frameworks {#frameworks}

Doom Emacs
<https://github.com/jkitchin/scimax> science emacs framework


## Packages {#packages}

<https://github.com/kaushalmodi/ox-hugo> org export for hugo
<https://github.com/mtekman/org-tanglesync.el> sync org mode files with dotfiles external to them
<https://github.com/alphapapa/matrix-client.el> emacs matrix client
<https://github.com/casouri/OrgMark> add drawings to org mode from your ipad
<https://github.com/yati-sagade/orch> add drawings to org mode from your android
<https://github.com/alraban/org-recoll> emacs binding for recoll text search engine
<https://github.com/cpitclaudel/quick-peek> peek at a window inline!
<https://github.com/legalnonsense/elgantt> gantt chart (??) in org
<https://github.com/progfolio/doct> declarative format for org capture templates
<https://github.com/jeremy-compostella/org-msg> minor mode for replying to outlook in nice outlook html


## Links {#links}

<https://www.youtube.com/watch?v=KdcXu%5FRdKI0&feature=youtu.be> -- getting more out
of org-capture
<https://www.reddit.com/r/emacs/comments/9iu6la/unemployed%5Fand%5Flearning%5Femacs/> --
somehow integrating images into org mode ?
<https://www.emacswiki.org/emacs/KeyChord> -- key chord: binding commands to
combinations of keystrokes
<https://github.com/NatTuck/doom-config/blob/master/config.el#L12> -- nat tuck's
configuration
<https://www.wisdomandwonder.com/article/10805/emacsorg-mode-choosing-the-best-writing-and-publishing-software>
-- org mode with latex - how to make things work well!

write your own emacs config for better speed
<https://blog.aaronbieber.com/2015/07/05/a-gentle-introduction-to-emacs-configuration.html>
<http://aaronbedra.com/emacs.d/>
<https://anuragpeshne.github.io/essays/emacsSpeed.html>
<https://www.emacswiki.org/emacs/ExampleConfigurations>
<https://github.com/munen/emacs.d>
<https://github.com/jhamrick/emacs>

<https://www.reddit.com/r/vim/comments/h8pgor/til%5Fconceal%5Fin%5Fvim/> --
concealing plaintext symbols with glyphs