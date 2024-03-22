# Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotation Examples

Some `code` goes here.

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


## Plain codeblock

A plain codeblock:
```
Some code here
def my function()
// some comment
```

## code for a specific language
Some more code with the `py` at the start:

```py
import pyautogui as py
def test()
    pass
```

```py title="test"
def test2()
    pass
```

```py linenums="1"
```

```py hl_lines="1 3"
def test1()
def test2()
def test3()
```