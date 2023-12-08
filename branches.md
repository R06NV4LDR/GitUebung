# Branches in Git

Branches sind ein leistungsstarkes Konzept in Git, das es Entwicklern ermöglicht, parallel an verschiedenen Aspekten eines Projekts zu arbeiten, ohne sich gegenseitig zu beeinflussen. Jeder Branch repräsentiert eine isolierte Entwicklungslinie mit seiner eigenen Historie von Commits.

## Erstellen eines Branches

Um einen neuen Branch zu erstellen, verwenden Sie den Befehl `git branch` gefolgt von einem Branch-Namen:

```bash```
git branch <Branch-Name>

Um zum neuen Branch zu wechseln, verwenden Sie:

git checkout <Branch-Name>

Alternativ können Sie beides in einem Schritt erledigen:

git checkout -b <Branch-Name>

##Arbeiten mit Branches

Nachdem Sie zu einem Branch gewechselt haben, können Sie Änderungen vornehmen, Commits erstellen und die Historie des Branches entwickeln, ohne die Hauptentwicklungslinie zu beeinflussen.

Um zu einem anderen Branch zu wechseln, verwenden Sie erneut git checkout:

git checkout <Anderer-Branch>

##Zusammenführen von Branches
Um Änderungen aus einem Branch in einen anderen zu integrieren, führen Sie einen Merge durch:

git checkout <Ziel-Branch>
git merge <Quell-Branch>

##Löschen eines Branches

Nachdem Änderungen aus einem Branch in den Hauptbranch übernommen wurden, kann der Branch gelöscht werden:

git branch -d <Branch-Name>

##Visualisierung von Branches
Hier ist eine Visualisierung, wie Branches in einem Git-Repository aussehen können:

Git Branches

Video: Arbeiten mit Git Branches


In diesem Beispiel habe ich einen Platzhalter für das Bild (`https://example.com/git-branches.png`) und das Video (`https://www.youtube.com/watch?v=XXXXXXX`) eingefügt. Ersetzen Sie diese durch tatsächliche URLs, die auf Ihre Ressourcen verweisen.

Um einen Link in Ihrer `README.md` auf diese neue Datei herzustellen, fügen Sie den folgenden Code hinzu:

```markdown```
[Weitere Informationen zu Branches](branches.md)

Dieser Link führt Benutzer von Ihrer README-Datei zur branches.md-Datei für detaillierte Informationen zu Branches.

## Review von Batuhan Seker

Ronny hat die Aufgabe sehr gut gelöst. Er hat alle wichtigen Informationen zu Branches in Git aufgeführt. Die Erklärungen sind sehr gut und verständlich. Die Bilder und Videos sind sehr gut gewählt und passen gut zum Thema. Die Aufgabe ist sehr gut gelöst und ich habe nichts zu bemängeln.