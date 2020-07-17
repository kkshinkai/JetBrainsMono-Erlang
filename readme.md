JetBrains Mono for Erlang
=========================

A patched version of original [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono), just changed the ligature `<=` to `=<`.

Change `settings.json` to this (in VSCode):

```json
{
    "editor.fontFamily": "JetBrains Mono",
    "[erlang]": {
        "editor.fontFamily": "JetBrains Mono Erlang"
    }
}
```