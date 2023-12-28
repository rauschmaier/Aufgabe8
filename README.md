# Vorbereitende Aufgaben

1. Laden Sie sich das [git e-Book](l"https://git-scm.com/book/de/v2") herunter.
2. Lesen Sie das Kapitel "Git Grundlagen" sowie "Git Branching" bis einschließlich "Einfaches Branching".

# Fragen

1. **Erklären Sie die unterschiedlichen git Status: untracked, unmodified, modified und staged.**

   - `untracked`: Die Datei wird von Git nicht verfolgt.
   - `unmodified`: Die Datei wurde dem Repository hinzugefügt, aber seitdem nicht geändert.
   - `modified`: Die Datei wurde geändert, aber noch nicht für den Commit vorgemerkt.
   - `staged`: Die Datei wurde für den nächsten Commit vorgemerkt.

2. **Wozu dient die `.gitignore`-Datei?**

   Die `.gitignore`-Datei wird verwendet, um Git mitzuteilen, welche Dateien und Verzeichnisse ignoriert werden sollen und nicht versioniert werden müssen.

3. **Wozu dient der Parameter "a" beim Commit? `git commit -a -m "Add new benchmark"`?**

   Der Parameter "-a" steht für "all" und bewirkt, dass alle Änderungen (sowohl modifizierte als auch gelöschte Dateien) automatisch für den Commit vorgemerkt werden.

4. **Sie möchten die Datei "Main.java" in Ihrem Git-Projekt in "ProjektX.java" umbenennen. Wie können Sie das tun?**

   Verwenden Sie den Befehl `git mv Main.java ProjektX.java` gefolgt von einem Commit.

5. **Wie können Sie die Commit-Historie im Terminal betrachten?**

   Verwenden Sie den Befehl `git log` im Terminal.

6. **Sie haben sich in einer Commit-Nachricht verschrieben und "Added new Path" statt "Added new Patch" geschrieben. Wie können Sie das ändern/rückgängig machen?**

   Verwenden Sie `git commit --amend` gefolgt von der korrigierten Commit-Nachricht.

7. **Erklären Sie, wozu `git restore --staged <file>` und `git restore <file>` verwendet werden können.**

   - `git restore --staged <file>`: Entfernt eine Datei aus dem Staging-Bereich, behält aber die lokalen Änderungen bei.
   - `git restore <file>`: Verwirft die lokalen Änderungen an einer Datei.

8. **Erklären Sie den Unterschied zwischen `git pull` und `git fetch`.**

   - `git pull`: Holen Sie Änderungen vom Remote-Repository und führen Sie ein Merge durch.
   - `git fetch`: Holen Sie Änderungen vom Remote-Repository, ohne sie zusammenzuführen. Sie müssen manuell einen Merge durchführen.

# Projektarbeit

1. Clonen Sie das Projekt auf Ihren Computer.
2. Wechseln Sie in das Git-Verzeichnis.
3. Legen Sie einen neuen Branch "Solution" an.
4. Wechseln Sie in den neuen Branch.
5. Beantworten Sie die Fragen in der "README.md"-Datei.
6. Fügen Sie die Datei dem Staging-Bereich hinzu, machen Sie einen Commit und pushen Sie den neuen Branch zum Remote-Repository.
7. Überprüfen Sie online, ob der `main`-Branch unverändert ist und es einen neuen Branch "solution" mit Ihren Lösungen gibt.
