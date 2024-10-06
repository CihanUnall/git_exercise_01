| Befehl                          | Erklärung                                                                                   |
|----------------------------------|---------------------------------------------------------------------------------------------|
| `mkdir gitExercise`              | Erstellt einen neuen Ordner mit dem Namen `gitExercise`.                                   |
| `cd gitExercise`                 | Wechselt in den gerade erstellten Ordner `gitExercise`.                                   |
| `git init`                       | Initialisiert ein neues Git-Repository.                                                   |
| `touch README.md`                | Erstellt eine neue Markdown-Datei mit dem Namen `README.md`.                               |
| `git add README.md`              | Fügt die Datei `README.md` zur Staging Area hinzu.                                        |
| `git commit -m "initial commit"` | Macht den ersten Commit mit der Nachricht "initial commit".                                |
| `git checkout -b structure`      | Erstellt einen neuen Branch namens `structure` und wechselt zu diesem Branch.              |
| `touch index.html`               | Erstellt eine neue HTML-Datei mit dem Namen `index.html`.                                  |
| `echo ... > index.html`          | Fügt die grundlegende HTML-Struktur in die `index.html`-Datei ein.                        |
| `echo "<h1>Hallo World!</h1>" >> index.html` | Fügt den `h1`-Tag mit dem Text "Hallo World!" zur `index.html`-Datei hinzu. |
| `git add index.html`             | Fügt die `index.html`-Datei zur Staging Area hinzu.                                       |
| `git commit -m "Add HTML structure with h1 tag"` | Macht einen Commit mit der Nachricht über die hinzugefügte HTML-Struktur. |
| `git checkout main`              | Wechselt zurück zum `main` Branch.                                                         |
| `git merge structure`            | Merged den `structure` Branch in den `main` Branch.                                       |
| `touch style.css`                | Erstellt eine neue CSS-Datei mit dem Namen `style.css`.                                    |
| `echo "h1 { color: red; }" > style.css` | Fügt CSS für rote Schriftfarbe des `h1`-Tags in die `style.css`-Datei ein.          |
| `git add style.css`              | Fügt die `style.css`-Datei zur Staging Area hinzu.                                        |
| `git commit -m "Add CSS for red h1 color"` | Macht einen Commit über die hinzugefügte CSS-Datei.                                      |
