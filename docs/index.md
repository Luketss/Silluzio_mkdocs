# md file sintax

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

Heading level 1
===============

Heading level 2
---------------

# Here's a Heading

Try to put a blank line before...

# Heading

...and after a heading. 

# Paragraphs

To create paragraphs, use a blank line to separate one or more lines of text.

## Markdown

I really like using Markdown.

I think I'll use it to format all of my documents from now on. 

## HTML
<p>I really like using Markdown.</p>

<p>I think I'll use it to format all of my documents from now on.</p>

## Blockquotes
To create a blockquote, add a > in front of a paragraph.
> Dorothy followed her through many of the beautiful rooms in her castle.

Nested Blockquotes

Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

# Code
At the command prompt, type `nano`.

At the command prompt, type <code>nano</code>. 

# Escaping Backticks
``Use `code` in your Markdown file.``

<code>Use `code` in your Markdown file.</code>


***

---

_________________


[md Sintax](https://www.markdownguide.org/basic-syntax/#code-blocks "md sintax").
[mkdocs-material](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown/ "mkdocs-material").
[mkdocs-material-reference](https://squidfunk.github.io/mkdocs-material/reference/grids/ "mkdocs-material-reference").


``` py title="code.py"
def main():
    print()
    print()
    print()
    print()
    print()
    print()
```