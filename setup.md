---
layout: page
title: Setup
permalink: /setup/
---

In preparation for this lesson, please make sure that you have a working Python interpreter installed on your computer.

1. Launch:
    - Terminal app on macOS
    - Terminal or Konsole on Linux
    - Terminal Emulator (MobaXTerm, Putty, GitBash, or similar) on Windows
2. Check you Python interpreter:

~~~
$ python -c "import sys; sys.exit(0)"
~~~
{: .source}

Make sure to not include `$`.

3. Clone this repository:

~~~
$ git clone https://github.com/swc-uiuc/python-testing.git
~~~
{: .source}

If you don't see any error messages then you are all set for the lesson!

4. *Optional*: If you would like to use the Jupyter (IPython) notebook for the lesson,
you should have already
[installed Anaconda](http://swcarpentry.github.io/workshop-template/#python)
which includes the notebook.

To start the notebook, open a terminal or git bash and type the command:

~~~
$ jupyter notebook
~~~
{: .source}

To start the Python interpreter without the notebook, open a terminal or git bash and type the command:

~~~
$ python
~~~
{: .source}
