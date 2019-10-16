# UK ISO Macos keymap with arrow and split keyboard layout

This is a keymap for DZ60 configured with arrows using the layout below:

[![](https://poitr.us/mARFK9+)](http://www.keyboard-layout-editor.com/#/gists/07d924064c77c0ff43de6b8a9519f931)

My build used the following components:
* DZ60 PCB
* [Stainless steel alu plate option A with 2U left shift](https://www.aliexpress.com/item/Alu-plate-dz60-plate-for-DIY-mechanical-keyboard/32827595666.html) (optional)
* [YMDK customized 61 64 68 ANSI keyset](https://www.amazon.com/Customized-Keyset-Profile-Mechanical-Keyboard/dp/B0777LMKKK)
* 60 Cherry MX Clear for the main keys + 10 Cherry MX Grey for the large keys
* [The wood case for DZ60](https://www.aliexpress.com/item/GH60-Keyboard-Wood-Case-PCB-Board-Position-Plate-Satellite-Axis-And-Walnut-Wood-Wrist-Rest-For/32836566852.html) (optional)

Base Layer
==========

~~~
Base layer - The new compact UK ISO mac keyboard with a split space bar.
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┐
│ESC│1  │2  │3  │4  │5  │6  │7  │8  │9  │0  │-  │=  │DEL│BKP│
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴───┤
│Tab  │Q  │W  │E  │R  │T  │Y  │U  │I  │O  │P  │[  │]  │Enter│
├─────┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┐    │
│Caps  │A  │S  │D  │F  │G  │H  │J  │K  │L  │;  │'  │\  │    │
├───┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬───┤
│Sft│`  │Z  │X  │C  │V  │B  │N  │M  │,  │.  │/  │END│^  │Sft│
├───┴┬──┴─┬─┴──┬┴───┴───┼───┴┬──┴───┴───┼───┼───┼───┼───┼───┤
│Ctrl│Opt │Com │Space   │Fn  │Space     │Com│Opt│<  │v  │>  │
└────┴────┴────┴────────┴────┴──────────┴───┴───┴───┴───┴───┘
~~~

* The grave key is kept to the right of the left shift to preserve easy keyboard identification macOS.
* The `Fn` key switch to the function layer (`_FL`).
* The right ***Space*** key is held down to switch to the media layer (`_ML`) see mappings below.
* The left ***Space*** key is held down to switch to the numpad layer (`_NL`) see mappings below.


Function Layer
==============

~~~
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┐
│   │F1 │F2 │F3 │F4 │F5 │F6 │F7 │F8 │F9 │F10│F11│F12│DEL│BKP│
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴───┤
│     │   │   │   │   │   │   │PgU│   │   │   │   │   │     │
├─────┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┐    │
│      │   │   │   │   │   │<  │v  │^  │>  │   │   │   │    │
├───┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬───┤
│   │   │   │   │   │   │   │   │PgD│   │   │   │   │   │   │
├───┴┬──┴─┬─┴──┬┴───┴───┼───┴┬──┴───┴───┼───┼───┼───┼───┼───┤
│    │    │    │        │    │          │   │   │   │   │   │
└────┴────┴────┴────────┴────┴──────────┴───┴───┴───┴───┴───┘
~~~

The function layer is activated by the `Fn` (`Hyper`) key to access `F` keys. Additionally the `HJKL` are mapped as cursor keys on that layer.


Media Layer
===========

~~~
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┐
│Ejt│Br-│Br+│   │   │   │   │Pre│Ply│Nxt│Mut│V- │V+ │   │   │
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴───┤
│     │   │   │   │   │   │   │   │   │   │   │   │   │Reset│
├─────┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┐    │
│      │   │   │   │   │   │   │   │   │   │   │   │   │    │
├───┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬───┤
│   │   │   │   │   │   │   │   │   │   │   │   │   │   │   │
├───┴┬──┴─┬─┴──┬┴───┴───┼───┴┬──┴───┴───┼───┼───┼───┼───┼───┤
│    │    │    │        │    │          │   │   │   │   │   │
└────┴────┴────┴────────┴────┴──────────┴───┴───┴───┴───┴───┘
~~~

The media layer is activated by the right `Space` key when held. It contains the typical macos media keys on the top row. Blank keys act as `Cmd+` that key on the base layer.


Numpad Layer
============

~~~
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┐
│   │   │   │   │   │   │   │   │%  │(  │)  │<  │>  │DEL│   │
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴───┤
│     │   │   │   │   │   │   │*  │ 0 │ 1 │ 2 │ 3 │   │     │
├─────┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┐    │
│      │   │   │   │   │   │   │ . │ - │ 4 │ 5 │ 6 │   │    │
├───┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬───┤
│   │   │   │   │   │   │   │   │ , │ = │ 7 │ 8 │ 9 │   │   │
├───┴┬──┴─┬─┴──┬┴───┴───┼───┴┬──┴───┴───┼───┼───┼───┼───┼───┤
│    │    │    │        │    │          │   │   │   │   │   │
└────┴────┴────┴────────┴────┴──────────┴───┴───┴───┴───┴───┘
~~~

The numpad layer is activated by the left `Space` bar, when held.