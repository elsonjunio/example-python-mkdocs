# Basic

## Navbar

```yaml
nav:
    - Home: index.md
    - Material Theme: theme.md
    - Basic: basic.md
```

## Markdown Extended

To extend markup instructions we will use PyMdown Extensions:

```
$ poetry add --dev pymdown-extensions
```

More information in [PyMdown Extensions](https://facelessuser.github.io/pymdown-extensions/)

## Format

 - **Bold** 
 - *italic* 
 - >quote.

List

1. fist one
2. last one

unordered list

- item A
- item B

code

`my_variable='definition'`

link

[DuckDuckGo](https://duckduckgo.com/)

image

![image](images/python_logo.png)

table

|Name|age|
|----|---|
|Elson| undefined|
|Duda|10|

 code block (fences)

```
def my_function:
    return 1
```

emoji :smile:

I don`t now
~~line~~

Mark

==Mark==

todo list

- [ ] todo

```{.py3 hl_lines="1-3 9" linenums="8" tile="main.py"}
#!/usr/bin/python3
# -*- coding: utf-8 -*-
#

# Start
if "__main__" in __name__:
    print('hello world')

# End of code

```

## custom fences 
See more in [Mermaid docs](https://mermaid-js.github.io/mermaid/#/)

Flowchart
[![](https://mermaid.ink/img/eyJjb2RlIjoiXG5ncmFwaCBURDtcbiAgICBBLS0-QjtcbiAgICBBLS0-QztcbiAgICBCLS0-RDtcbiAgICBDLS0-RDtcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In19)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiXG5ncmFwaCBURDtcbiAgICBBLS0-QjtcbiAgICBBLS0-QztcbiAgICBCLS0-RDtcbiAgICBDLS0-RDtcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In19)

Sequence diagram
[![](https://mermaid.ink/img/eyJjb2RlIjoiXG5zZXF1ZW5jZURpYWdyYW1cbiAgICBwYXJ0aWNpcGFudCBBbGljZVxuICAgIHBhcnRpY2lwYW50IEJvYlxuICAgIEFsaWNlLT4-Sm9objogSGVsbG8gSm9obiwgaG93IGFyZSB5b3U_XG4gICAgbG9vcCBIZWFsdGhjaGVja1xuICAgICAgICBKb2huLT4-Sm9objogRmlnaHQgYWdhaW5zdCBoeXBvY2hvbmRyaWFcbiAgICBlbmRcbiAgICBOb3RlIHJpZ2h0IG9mIEpvaG46IFJhdGlvbmFsIHRob3VnaHRzIDxici8-cHJldmFpbCFcbiAgICBKb2huLS0-PkFsaWNlOiBHcmVhdCFcbiAgICBKb2huLT4-Qm9iOiBIb3cgYWJvdXQgeW91P1xuICAgIEJvYi0tPj5Kb2huOiBKb2xseSBnb29kIVxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifX0)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiXG5zZXF1ZW5jZURpYWdyYW1cbiAgICBwYXJ0aWNpcGFudCBBbGljZVxuICAgIHBhcnRpY2lwYW50IEJvYlxuICAgIEFsaWNlLT4-Sm9objogSGVsbG8gSm9obiwgaG93IGFyZSB5b3U_XG4gICAgbG9vcCBIZWFsdGhjaGVja1xuICAgICAgICBKb2huLT4-Sm9objogRmlnaHQgYWdhaW5zdCBoeXBvY2hvbmRyaWFcbiAgICBlbmRcbiAgICBOb3RlIHJpZ2h0IG9mIEpvaG46IFJhdGlvbmFsIHRob3VnaHRzIDxici8-cHJldmFpbCFcbiAgICBKb2huLS0-PkFsaWNlOiBHcmVhdCFcbiAgICBKb2huLT4-Qm9iOiBIb3cgYWJvdXQgeW91P1xuICAgIEJvYi0tPj5Kb2huOiBKb2xseSBnb29kIVxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifX0)

Gantt diagram
[![](https://mermaid.ink/img/eyJjb2RlIjoiZ2FudHRcbmRhdGVGb3JtYXQgIFlZWVktTU0tRERcbnRpdGxlIEFkZGluZyBHQU5UVCBkaWFncmFtIHRvIG1lcm1haWRcbmV4Y2x1ZGVzIHdlZWtkYXlzIDIwMTQtMDEtMTBcblxuc2VjdGlvbiBBIHNlY3Rpb25cbkNvbXBsZXRlZCB0YXNrICAgICAgICAgICAgOmRvbmUsICAgIGRlczEsIDIwMTQtMDEtMDYsMjAxNC0wMS0wOFxuQWN0aXZlIHRhc2sgICAgICAgICAgICAgICA6YWN0aXZlLCAgZGVzMiwgMjAxNC0wMS0wOSwgM2RcbkZ1dHVyZSB0YXNrICAgICAgICAgICAgICAgOiAgICAgICAgIGRlczMsIGFmdGVyIGRlczIsIDVkXG5GdXR1cmUgdGFzazIgICAgICAgICAgICAgICA6ICAgICAgICAgZGVzNCwgYWZ0ZXIgZGVzMywgNWRcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In19)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ2FudHRcbmRhdGVGb3JtYXQgIFlZWVktTU0tRERcbnRpdGxlIEFkZGluZyBHQU5UVCBkaWFncmFtIHRvIG1lcm1haWRcbmV4Y2x1ZGVzIHdlZWtkYXlzIDIwMTQtMDEtMTBcblxuc2VjdGlvbiBBIHNlY3Rpb25cbkNvbXBsZXRlZCB0YXNrICAgICAgICAgICAgOmRvbmUsICAgIGRlczEsIDIwMTQtMDEtMDYsMjAxNC0wMS0wOFxuQWN0aXZlIHRhc2sgICAgICAgICAgICAgICA6YWN0aXZlLCAgZGVzMiwgMjAxNC0wMS0wOSwgM2RcbkZ1dHVyZSB0YXNrICAgICAgICAgICAgICAgOiAgICAgICAgIGRlczMsIGFmdGVyIGRlczIsIDVkXG5GdXR1cmUgdGFzazIgICAgICAgICAgICAgICA6ICAgICAgICAgZGVzNCwgYWZ0ZXIgZGVzMywgNWRcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In19)

### Export PDF

```shell
$ poetry add --dev mkdocs-with-pdf
```

```{.yml tile="mkdocs.yml"}
plugins:
    - with-pdf
```

More information in [MkDocs PDF Export Plugin](https://github.com/zhaoterryy/mkdocs-pdf-export-plugin)

### Converte Mermaid Diagrams

```shell
$ npm install -g mermaid-js-converter
```

```shell
$ mjc -f basic_svg.md -o SVG
```
More information in [mermaid-js-converter](https://github.com/superj80820/mermaid-js-converter)

