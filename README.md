# Function-Call-Tracer
Function Call Tracer (with function names) using _penter / p_exit hooks.<br>
Uses *.map files from compiled programs to get function names<br>
<br>In C++ best example on all of github
<br>
Add these files to an x32 c++ project ( for x64 you need to move the inline assembly in an asm file )<br>
compile with /Gh flag<br>
at some point ( after main ? ) enable logging with function : StartLogFunctionEntrances()<br>

```
requires "/Gh" compile flag !!!
to add exit tracking, add /GH !!!
you need to disable incremental linking for function name lookup to work
```

