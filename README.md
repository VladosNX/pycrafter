# PyCrafter

V1.0 Beta

## About

PyCrafter is a template engine for Python and another languages.

You can insert big part of code without functions in program.

## How to use

You can see manual in PyCrafter - after installing, run

> pycrafter --doc

and you will see manual.

### Creating config

In config you set variables. These are .py files.

Example:

	my_var = 'There is a rain on the street.'

### Using variables

To use variables, insert $[my_var]$ to code. Replace my_var to

name of your variable.

### Example

**config.py**

	my_var = 'There is a rain on the street.'

**main.py**

	print("$[my_var]$")
	
**Result**

	print("There is a rain on the street.")

### Crafting template

To craft template, run

> pycrafter -c template.py config.py ready-template.py

Here are:

- **template.py** - name of template

- **config.py** - name of config

- **ready-template.py** - output file

Have a good coding!