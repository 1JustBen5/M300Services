# Git CheatSheet
Erstellt von [Benneth Gripp](https://github.com/1JustBen5) am 05.03.2021

---
# Git Basic-Befehle
**Um ein neues repository zu initalisieren:**
```
git innit <directory>
```

**Um ein schon existierendes repository a den PC zu kopieren:**
```
git innit <directory>
```

**Wenn man nun veränderte / neue Daten commiten will kann man mit dem Folgenden Command gleich einen Ganzen ordner oder einzelne Dateien commiten:**
```
git innit <directory/file>
```

**Wenn man mit einem Commentar commiten will:**
```
git innit <directory/file>
```

---

# Git Stage & Snapshot Befehle
**Geänderte Dateien im Arbeitsverzeichnis anzeigen, die für die nächste Datenübergabe bereitgestellt werden**
```
git status 
```

**Eine Datei, so wie sie aktuell aussieht, zu der nächsten Datenübertragung (stage) hinzufügen**
```
git add [file]
```

**Löscht die gestageden änderungen wieder**
```
git reset [file]
```
**Unterschied dessen, was sich verändert, aber nicht staged ist**
```
git diff
```

**Unterschied zwischen gestaged, aber noch nicht committed wurde**
```
git diff --staged
```
