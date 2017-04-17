<h1 align="center">
<a href="https://github.com/xtensis-editor/xtensis">
<img src="media/logos/PNG/xtensis-256.png" alt="Xtensis Editor" width="256" height="256"/>
</a><br>
<a href="https://github.com/xtensis-editor/xtensis">Xtensis Editor</a>
</h1>

<h4 align="center">Extendable editing: defy the norm.</h4>

# The Xtensis Project

## Core goals

* Minimal

It is aimed to keep Xtensis as MINIMAL as possible. That is to say, no
bullshit. We don't want games like Tetris in Xtensis Core, but if
users _want_ to have Tetris in their _own individual_ setup, then they
should be subjected to very little opposition to that. Tetris is a fun
game, but there's NO reason to keep it in Xtensis Core.

* Extendable

One of Xtensis's core goals is to be as extendable as possible, in a
similar manner to GNU Emacs. Emacs is good for extensions, but is
limited by only *one* language - Emacs LISP. 

Xtensis works around this defining a small, extendable JSON-RPC server
in the core, and accepting requests from many XTCAPI (Xtensis Core
API) libraries, such as ones written in Python, Lua or even GNU
Guile!

At its core, Xtensis is merely a JSON-RPC server which is easily
extended by RPC requests from modules connected to it. 

* Modular

Xtensis should be as modular as possible, to keep the core size down,
and to allow *maximum flexibility*.

## History

Xtensis started life as `slacs`, and those who followed its progress
in those times will remember it in those infancy stages, and while I
(@shymega) was developing my ideas further and in new directions.
