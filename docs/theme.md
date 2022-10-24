
# Material Theme

In this example we will use Material for MkDocs, you can see more in MkDocs [Choosing your Theme](https://www.mkdocs.org/user-guide/choosing-your-theme/).


### Install
To install Material for MkDocs we can use the below  command:

```shell
$ poetry add --dev mkdocs-material
```

After installation we must add the following lines to mkdocs.yml

```yml
theme:
  name: material
```

To test we can use the below command do build and start a http server:

```shell
$ mkdocs serve
INFO     -  Building documentation...
INFO     -  Cleaning site directory
INFO     -  Documentation built in 0.31 seconds
INFO     -  [12:12:30] Watching paths for changes: 'docs', 'mkdocs.yml'
INFO     -  [12:12:30] Serving on http://127.0.0.1:8000/
```

Change the palette

```yml
theme:
  name: material
  palette:
    - scheme: default
      primary: purple
      toggle:
        icon: material/weather-night
        name: Dark Mode
    - scheme: slate
      primary: deep purple
      toggle:
        icon: material/weather-sunny
        name: Clean Mode

```

