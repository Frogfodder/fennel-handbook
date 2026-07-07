# Introduction to Fennel

Fennel is a Lisp-like programming language that compiles to Lua.

It combines the simplicity and portability of Lua with the expressive power of Lisp syntax. Since Fennel compiles to Lua, Fennel programs can run anywhere Lua is available.

## First example

**Fennel**

```
(print "Hello from Fennel!")
```
corresponds to:

**Lua**
```
print("Hello from Lua!")
```
**Why Fennel?**

Fennel exists to make Lua more expressive without losing its simplicity.

Compared to Lua, Fennel adds:

prefix notation (Lisp style)<br>
powerful macros<br>
better code composition<br>
structural clarity for complex programs

**Interactive use (REPL)**

Fennel can be used interactively:

**Key idea**
Fennel is not a replacement for Lua.<br>
It is a *different way to write Lua.*
