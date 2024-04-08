# rism-syntax

Auto complete and Syntax highlighter for '.rism'

## Auto complete

| Type    | Result                      |
|---------|-----------------------------|
| `{{`    | `{{ }}`                     |
| `{%`    | `{% %}`                     |
| `{% if` | `{% if %} {% endif %}`      |
| `{% ifel` | `{% if %} {% else %} {% endif %}` |
| `{% for` | `{% for %} {% endfor %}`    |

## Syntax highlighter

| Element                | Color   |
|------------------------|---------|
| tag                    | yellow  |
| everything between     | blue    |

Tested on VSCode Dark Modern (default) theme.
