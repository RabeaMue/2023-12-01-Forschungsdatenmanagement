# Ein Git-Repositorium für den Kurs erstellen

# Schritt 1 - Ordner und Dateien erstellen

Öffne das Terminal in deiner Ubuntu VM und gehe zu deinem Repositorium.

Erstelle einen Unterordner

```
mkdir Modul_4
```

Und erstelle in diesem Unterordner eine weitere Markdown-Datei mit
einer Überschrift.

```
echo "Modul 4" > Modul_1/README.md
```

## Schritt 2 - Lokales Git-Repositorium erstellen und Dateien hinzufügen


Führe die beiden neuen Dateien in die Staging-Area

```
git add README.md Modul_4/README.md
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

Füge deine Gruppenmitglieder, Konrad (GitHub-Name: konrad) und Rabea (GitHub-Name: RabeaMue) als Collaborator auf GitHub hinzu:  
"Settings" > "Collaborators" und dort den Nutzernamen eingeben.  

Deine Gruppenmitglieder kannst du auf Moodle auf der Startseite von Modul 4 unter den Gruppenchats einsehen.
