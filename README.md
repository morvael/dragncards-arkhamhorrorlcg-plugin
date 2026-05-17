## Dragncards plugin

An AHLCG plugin for Dragncards.

### Kate support

Included are two files which make editing any Dragncards plugin JSON files in Kate editor a much more pleasant experience.

Syntax file `Dragnlang.xml` should be copied to (or symlinked to):
```
~/.var/app/org.kde.kate/data/org.kde.syntax-highlighting/syntax
```

Theme file `Arkham Dark.theme` should be copied to (or symlinked to):
```
~/.var/app/org.kde.kate/data/org.kde.syntax-highlighting/themes
```

Above paths work for Flatpak version of Kate on Linux. They might be different on other OSes or when using different install methods. Please refer to Kate's documentation for a valid path if your setup is different.
