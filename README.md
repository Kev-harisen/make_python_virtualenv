make_python_virtualenv
====
Automatically create python virtualenv

## Description
If you use this script, you can create python virtual environment with pythonz, direnv, and virtualenv. Direnv enable you to automatically switch virtual environments when you chage directories.

## Install and Requirements
Before using, you must install
- pythonz
- direnv
- virtualenv on system python

Then, you move code "mkvenv" to your directory which your computer can search.
Now, you can use "mkvenv" command.

## Usage
Before using, you must install python 3.5.3 with pythonz.

Defalut
`mkvenv directory`

If you want to use specific version of Python, you will use -v option.
`mkvenv -v 3.6.0 directory`


