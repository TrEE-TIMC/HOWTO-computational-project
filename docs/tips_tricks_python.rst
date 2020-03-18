======================================
Tips and tricks writing code in Python
======================================

- Use a good text editor.

  - `atom <https://atom.io/>`_
  - vim, emacs if you know how to use those text editors already.

- Look at your data and results as much as you can. That's an excellent way to
  ensure the code you are writing is correct.

- Configure your text editor to perform static checks on your code using
  `flake8 <https://flake8.pycqa.org/en/latest/>`_. ``flake8`` is a tool that
  will tell you (1) if there are mistakes and typos in your code immediatly;
  (2) enforce Python's default style guide `pep8
  <https://www.python.org/dev/peps/pep-0008/>`_ on your code.

- Be familiar with `PEP8 <https://www.python.org/dev/peps/pep-0008/>`_. Proper
  formatting of your code with reduce cognitive load with writing and reading
  it.


Useful packages
---------------

- `argparse: <https://docs.python.org/3/library/argparse.html>`_ to easily
  make user-friendly command-line interfaces.

- `ipython <https://ipython.org/install.html>`_ for interactive python usage.
  Comes with a powerful debugging and profiling tool. Allows to run any
  script in ipython and play with the outputs.

- `memory-profiler <https://pypi.org/project/memory-profiler/>`_ to monitor
  memory usage of a program.
