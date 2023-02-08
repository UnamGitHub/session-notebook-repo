### Session 2 Protocol Copy

---

date: 07.02.2023, Tuesday
author: Coach Jessica
next-author: Anja

---

## Checkliste

(bitte löschen, wenn alles erledigt ist)

- [ ] Screenshot für [Anwesenheit](#anwesenheit) eingetragen (**Wichtig:** Datum, Uhrzeit und [Namen aller Teilnehmer:innen]() vorhanden?)
- [ ] `next-author` eingetragen
- [ ] `README.md` aktualisiert
- [ ] `README.md` in der Vorschau geprüft
- [ ] Vorschau dieser Seite geprüft

---

## Themen

- Shell Basics
- Git CLI and remote

---

## Notizen

### Shell Basics

- [Handout Shell Basics](../sessions/shell-basics/shell-basics.md)

- `clear` räumt das aktuelle Terminal-Fenster auf, aber alle vergangenen Befehle/Ereignisse sind durch einfaches Hochscrollen wieder sichtbar - die Kommandos sind also nicht gelöscht, sondern nur nach oben verschoben
- `cmd K` lässt die eingegebenen Kommands verschwinden, das heisst auch durch Hochscrollen können wir diese nicht wieder sichtbar machen
- `history` zeigt euch alle vorherig eingetippten Kommandos an, aber auch nur die Kommandos und nicht die zugehörigen Ergebnisse
- `brew list` zeigt eine Liste aller installierten **Homebrew packages** an
- `Command + Shift + .` versteckte folder/files im macOS finder anzeigen lassen
- `ls -a` (all) Flag - listet versteckte Dateien auf
- [Homebrew Formulae](https://formulae.brew.sh/cask/): Liste von `casks` (applications) die über den Homebrew package manager installiert werden können

---

### Git CLI and Remote

- [Handout Git CLI and Remote](../sessions/git-cli-and-remote/git-cli-and-remote.md)
- `git rm --cached .DS_Store` entfernt die Datei ".DS_Store" aus der git staging area.
  - `--cached` wird verwendet, um die Datei aus dem Staging-Bereich zu entfernen, ohne sie aus dem Dateisystem zu löschen
- `git remote set-url origin git@github.com:{USERNAME}/{PROJECTNAME}.git`, um das Repository von HTTPS zu SSH zu wechseln.

  - `git remote` Befehl, um Verbindungen zu anderen Repositorys zum erstellen, anzeigen und löschen.
  - `set-url` Option, mit der die URL eines vorhandenenRepositorys aktualisiert wird.
  - `origin` ist der Name des entfernten Repositorys, das Sie aktualisieren möchten.

- [Git Security SSH](https://www.w3schools.com/git/git_security_ssh.asp?remote=github)

### The Git Workflow

![git-workflow-simple](../images/assets/git-workflow-simple.png)

---

## Aufgaben

- [Challenge Shell Basics](../sessions/shell-basics/challenges-shell-basics.md)

- [Challenge Git CLI and remote](../sessions/git-cli-and-remote/challenges-git-cli-and-remote.md)

---

## Weiteres Material & Links

- [git Atlassian Tutorials](https://www.atlassian.com/git/tutorials/what-is-version-control)
- [git Documentation](https://git-scm.com/doc)

---

## Anwesenheit

![2023/02/06](../images/week1/WD_CGN_23.1_07.02.2023.png)
