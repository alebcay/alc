alc
===

CLI for the Alcatraz package manager

### Usage


Installing color themes

```
alc install Cobalt
alc install Tomorrow
```

and plugins

```
alc install CocoaPods
alc install ClangFormat
```

work right now. File and project templates are **not** supported at this time (they often have complex installation procedures, and I have yet to implement a universal way of installing these).

Similarly,

```
alc uninstall Cobalt
alc uninstall Tomorrow
alc uninstall CocoaPods
alc uninstall ClangFormat
```

### Known Issues/Important Notes

* As aforementioned, `alc` does **not** have support for file/project templates at this time
* All package names **ARE** case-sensitive!
