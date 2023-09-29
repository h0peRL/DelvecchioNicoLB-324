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
![image](https://github.com/h0peRL/DelvecchioNicoLB-324/assets/89131248/0bab8b10-9c89-47b2-8ca3-a57f4faa6d99)
![image](https://github.com/h0peRL/DelvecchioNicoLB-324/assets/89131248/e29d79e2-174c-4974-8673-e26bffbc582d)
![image](https://github.com/h0peRL/DelvecchioNicoLB-324/assets/89131248/0a4387d4-e71c-4c00-b24a-e772e38abddc)

