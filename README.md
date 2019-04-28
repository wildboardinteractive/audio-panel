Gnome-Shell Extension Audio-Panel
===========================================

This extension allows you to control the volume of multiple output ports 
on a single device, or change devices rapidly. It is based on Audio-Output-Switcher
by @anduchs.

https://github.com/adaxi/audio-output-switcher

The default shortcut keys are: 
`<Super>`+`q` : Switch output sink
`<Super>`+`e` : Switch output sink port

I am planning to look at adding input selection for line inputs and microphones.

Install
-------

Either via 

    https://extensions.gnome.org

or via

    git clone https://github.com/wildboarinteractive/audio-panel.git ~/.local/share/gnome-shell/extensions/audio-panel@wildboarinteractive

Then resart the gnome-shell via `Alt+F2` then `r` and enable the extension using gnome-tweak-tool

To update later, just issue

    (cd ~/.local/share/gnome-shell/extensions/audio-panel@wildboarinteractive && git pull)
    
Credits
-------

Forked from original extension by @anduchs.
