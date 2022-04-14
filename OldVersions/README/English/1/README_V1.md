
***

![/Lua-Logo.svg](/Lua-Logo.svg)

### Learning Lua

I am not too experienced with Lua at the moment. This document will go over my knowledge of the Lua language so far.

This document used version 5.4 of the Lua programming language.

#### Comments in Lua

Comments in Lua are the same as comments in languages like Ada, SQL, Haskell, VHDL, Elm, etc.

```lua
-- This is a single line comment
-- Lua does not support multi-line comments (as far as I know)
```

#### Break keyword in Lua

```lua
break
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Hello World in Lua

A hello world program in Lua is pretty simple. It is similar to Python, Perl, etc..

```lua
print ("Hello World")
```

It can also be written without parentheses

```lua
print "Hello World"
```

And doesn't require double quotation marks (singluar quotes work as well)

```lua
print 'Just another Lua hacker'
```

#### Functions in Lua

The process of making functions in Lua is pretty simple:

```lua 
-- An empty function
local function1
function1 = function() end
function1()
-- A hello world function
local function2
function2 = function()
	print("Hello World function has functionally functioned")
end
function2()
```

_/!\ This example has not been tested yet, and may not work_

##### Calling a function in Lua

Calling a function in Lua is very easy, and similar to many languages, such as Python, MoonScript, Rust, C, etc.

```lua
function1()
```

#### Classes in Lua

Classes are supported in Lua. They can be defined like so:

```lua
local myLuaClass
do
	print("Welcome to my Lua class")
end
```

_/!\ This example has not been tested yet, and may not work_

#### Source

The majority of my Lua knowledge comes from [the official MoonScript developer reference](https://moonscript.org/reference/) it has proven extremely helpful for both MoonScript and Lua, although some of my knowledge comes from self-experimentation with Lua and Wikipedia.

#### Other knowledge of Lua

1. Lua is a curly bracket language, but does not use semicolons at the end of each line

2. MoonScript and Amulet are languages that compile to Lua

3. Lua uses the `.lua` file extension

4. Lua was created in 1993

5. Lua is an open source programming language

6. No other knowledge of Lua at the moment.

***

**File version:** `1 (2022, Wednesday, April 13th at 8:11 pm PST)`

***
