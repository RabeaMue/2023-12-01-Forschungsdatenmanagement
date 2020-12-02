# Ein Git-Repositorium für den Kurs erstellen

# Schritt 1 - Ordner und Dateien erstellen

Öffne das Terminal in deiner Ubuntu VM und gehe zu deinem Repositorium.

Erstelle einen Unterordner

```
mkdir Modul_1
```

Und erstelle in diesem Unterordner eine weitere Markdown-Datei mit
einer Überschrift.

```
echo "Modul 1" > Modul_1/README.md
```

## Schritt 2 - Lokales Git-Repositorium erstellen und Datein hinzufügen


Führe die beiden neuen Dateien in die Staging-Area

```
git add README.md Modul_1/README.md
```

und commite die Änderungen in das Repositorium.

```
git commit -m "Initial commit"
```

Pushe deine Änderung in dein GitHub Repositorium

```
git push
```

## Schritt 3 - Collaborator in GitHub hinzufügen

Füge deine/n Partner/in, Konrad (konrad) und Rabea (RabeaMue) als Collaborator auf GitHub hinzu: "Settings" >
"Collaborators" und dort den Nutzernamen eingeben.


## Schritt 4 - Fügt Eure Dateien hinzu

Fügt Eure Dateien (Jupyter Notebook, Skripte) zu dem Repositorium
lokal hinzu und pusht die Änderungen zu GitHub.

## Schritt 5 - Ordner für Modul 2 und 3 anlegen

Wiederholt Schritt 1 und Schritt 2 für Modul 2 und Modul 3
