# LB 324

## Aufgabe 2
Ich habe ein .pre-commit-config.yaml file erstellt, indem ich die ganzen notendigen sachen implementiert habe.

dafür muss man einige sachen installieren:
Erklären Sie hier, wie man pre-commit installiert.

Wenn man ein Python Projekt hat, geht das eigentlich ziemlich einfach.

Windows
```pip install pre-commit```

OSX
```pip3 install pre-commit```

ebenfalls auch
```pip install -r requirements.txt```

Danach erstellt man seinen Pre-Commit Hook. Als Beispiel habe ich hier meines im folder und die datei heisst:
```.pre-commit-config.yaml```

Jetzt führt man noch den folgenden Befehl im Terminal aus.
```pre-commit install --hook-type pre-commit --hook-type pre-push```

Jetzt ist man eigentlich schon einsatzbereit und man kann nun nur Commits machen, wenn alle Tests erfolgreich durchlaufen.

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
