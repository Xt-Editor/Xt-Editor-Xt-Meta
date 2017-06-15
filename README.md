<h1 align="center">
<a href="https://github.com/xt-editor/xt">
<img src="media/logos/PNG/xt-256.png" alt="Xt Editor" width="256" height="256"/>
</a><br>
<a href="https://github.com/xt-editor/xt">Xt Editor</a>
</h1>

<h4 align="center">Extendable editing: defy the norm.</h4>

# The Xt Project

## History

Xt started life as `slacs`, and those who followed its progress
in those times will remember it in those infancy stages, and whilst I
(@shymega) was developing my ideas further and in new directions.

## Core goals

* Minimal

It is aimed to keep Xt as _minimal_ as possible. That is to say,
no bullshit. We don't want games like Tetris in Xt Core, but if
users _want_ to have Tetris in their _own individual_ setup, then they
should be subjected to very little opposition to that. Tetris is a fun
game, but there's **no** reason to keep it in Xt Core.

* Extendable

One of Xt's core goals is to be as extendable as possible, in a
similar manner to GNU Emacs. Emacs is good for extensions, but is
limited by only *one* language - Emacs LISP. 

Xt works around this defining a small, extendable JSON-RPC server
in the core, and accepting requests from many XTCAPI (Xt Core
API) libraries, such as ones written in Python, Lua or even GNU
Guile!

At its core, Xt is merely a JSON-RPC server which is easily
extended by RPC requests from modules connected to it. 

* Modular

Xt should be as modular as possible, to keep the core size down,
and to allow *maximum flexibility*.

## Installing

To install Xt, follow [these][Xt-install] instructions to
install it. Thanks for trying Xt out! ^-^

## Contributing

If you want to contribute to Xt, XOR the projects that are a part
of it, feel free to contact me on IRC, and we can discuss ideas. I can
be found on Freenode, on #Xt-editor.

[xt-install]: /INSTALL.md
