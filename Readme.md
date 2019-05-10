

What is this? 
=============
This is a very simple screen rotation script for the sway window manager. It reads the rotation state of the currently active monitor and then issues a command to change the rotation to the next one, according to the transition list starting on line 35 of the script. The script does not actually maintain any state, it just issues commands to the window manager using swaymsg. 

So, for example, in the default installation if your screen is in a normal un-rotated state and you

`./sway-rotate`

your screen will now be rotated to 90 degrees. If you issue the command again, it should rotate back to normal. As noted above, the specific order of the rotation states can be changed by modifying the python dictionary on line 35 of the code. 

Requirements
============
Requires python3. And sway, of course. 


Installation
============
It is just a script. Pop it in your .bin directory if you have one, it should just work. 

---

License
=======
This is a tiny script that anyone could come up with in an hour if they needed, so I have used the unlicense license. Do whatever you want with it, really just have fun.  

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>

---
