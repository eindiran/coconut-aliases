# coconut-aliases
This repo was created to store two very simple bash scripts I've found useful while using coconut. Leverage [mypy](http://mypy-lang.org) everytime your code is compiled into python!

You can find the current coconut docs [here.](https://media.readthedocs.org/pdf/coconut/develop/coconut.pdf)
More info about the language can be found on their official [site.](http://coconut-lang.org)

## cocoa
The `cocoa` command compiles the input file to python3.5, with mypy enabled. It preserves the functionality of `coconut-run` by allowing the user to specify the `--run` flag, causing the produced python code to be run after compilation.

## cocoa2
The `cocoa2` command works in much the same way as the `cocoa` command, except for changing the target python from 3.5 to 2.7.
