# Open Things URL

This workflow can open Things URLs which can be created [here](https://culturedcode.com/things/support/articles/2803573/).

Just create a URL for your project, add a new item to the "Open URL" list filter, choose a title (and icon if you want) and set the URL as 'arg'.

> Feel free to remove the existing items. They will not work on your machine anyway.

Now you can try executing it (default keyword is 't').

You can also dynamically insert values into your URLs. The following variables do currently exist:

| variable | value                     |
| -------- | ------------------------- |
| `{date}` | current date (DD.MM.YYYY) |

You can change this or add your own variables by editing the bash script.
