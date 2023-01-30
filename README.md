<div align="center">
<img align="center"  width="auto" height="auto" src="https://nuwe.io/images/Group-3-3.png" />
<br/>

<div id="user-content-toc">
  <ul>
    <summary><h1 style="display: inline-block;">Python Algorithmia</h1></summary>
  </ul>
</div>

</div>

## Relevant Info

• coverage: is a tool that helps measure the amount of code that is executed during tests. <br/>
• logzero: is a library that provides an interface for zero-level logging, like syslog and eventlog. <br/>
• pycodestyle: is a tool that helps detect style issues in Python code, based on the rules of PEP 8. <br/> 
• pyflakes: is a linting tool for Python that detects errors in code, such as unused variables or missing imports. <br/>
• pylint: is a linting tool for Python that detects style issues and errors in code. It also provides a code quality rating. <br/>
• flake8: is a linting tool for Python that combines the functionality of pyflakes, pycodestyle and McCabe. <br/>
• python-coveralls: is a tool that helps upload code coverage information to the coveralls.io platform, allowing for visualization of statistics and code coverage graphs.

## How to use

1. pip install -r requirements.txt

2. python src/hello.py

3. python -m unittest tests/test_hello.py

## Examples

```bash
$ make
Some available commands:
 * run          - Run code.
 * test         - Run unit tests and test coverage.
 * doc          - Document code (pydoc).
 * clean        - Cleanup (e.g. pyc files).
 * code-style   - Check code style (pycodestyle).
 * code-lint    - Check code lints (pyflakes, pyline).
 * code-count   - Count code lines (cloc).
 * deps-install - Install dependencies (see requirements.txt).
 * deps-update  - Update dependencies (via pur).
```

```bash
$ make test
[D 180728 04:10:10 hello:23] <function print_message at 0x107867aa0>
Hello world!
[I 180728 04:10:10 hello:47] []
.
----------------------------------------------------------------------
Ran 1 test in 0.001s

OK
Name                  Stmts   Miss  Cover
-----------------------------------------
src/__init__.py           0      0   100%
src/hello.py             26      0   100%
tests/__init__.py         0      0   100%
tests/test_hello.py      12      0   100%
-----------------------------------------
TOTAL                    38      0   100%
```

## License

This project is licensed with the [MIT license](LICENSE).

<p align="center">
  Made with ❤️ by <a href="https://nuwe.io">Nuwe</a>
</p>
