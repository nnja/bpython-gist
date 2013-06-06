bpython + clean code + gist integration
=========

bpython-gist is a pastebin_helper extension for bpython

What you get:

* **Clean Code:** the exported output can be run as a python script with no modification. Any output values and errors from the repl are preserved as comments.
* **Gist Integration:** the export is uploaded to an anonymous gist, giving you the ability to star it, fork it, or embed it.

Screen-Shots
--------

**Your repl**

![bpython repl](https://raw.github.com/nnja/bpython-gist/master/img/bpython.png)

**The default behavior exports indentation guides and uses bpaste**
![default behavior](https://github.com/nnja/bpython-gist/blob/master/img/default.JPG?raw=true)

**The improved behavior removes indentation guides, comments out and annotates the output, then uploads the result as an anonymous gist**

![clean gist](https://github.com/nnja/bpython-gist/blob/master/img/gist.JPG?raw=true)

Requirements
--------
* python 2.7 or greater
* bpython version 0.12 [Download the latest release](http://bpython-interpreter.org/downloads/)

Installation
--------

1. **Download [gist.py](https://raw.github.com/nnja/bpython-gist/master/gist.py), and add it to a location in your path.**

2. **Open your bpython configuration file, or create one if it doesn't exist.**

```
cd ~
mkdir .bpython; chdir .bpython
touch config
```

3. **Add the following entries to your config file**

```
[general]
pastebin_helper=gist.py
```

You're done!

Additional Documentation
--------
* [pastebin_helper configuration](http://docs.bpython-interpreter.org/configuration.html#pastebin-helper)
* [general bpython configuration](http://docs.bpython-interpreter.org/configuration.html)