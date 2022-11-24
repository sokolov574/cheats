# Benutzer
- `Id` - Detaillierte Informationen über den - Benutzer (uid, gid und Gruppe).
- last - Eine Liste mit Informationen über die letzten Anmeldungen, einschließlich Zeit, Benutzername, IP-Adresse und Sitzungsdauer.
- who - Autorisierte Benutzer anzeigen
- groupadd "testgroup" - Erstellt eine Gruppe mit dem Namen "testgroup".
- adduser NewUser – Fügt einen Benutzer namens „NewUser“ hinzu.
- userdel NewUser - Löscht einen Benutzer namens "NewUser".
- usermod NewUser - Ändert Informationen über den Benutzer "NewUser".

#Katalognavigation
- CD/. - Wechseln Sie in das Hauptverzeichnis
- cd - Gehe ins Home-Verzeichnis ($HOME-Variable)
- cd /root - Wechseln Sie in das /root-Verzeichnis
- cd .. - Gehe eine Ebene tiefer
- cd /root/.ssh - Wechseln Sie in den versteckten Ordner .ssh

#Arbeiten mit Dateien
- ls -al - Dateien und Verzeichnisse im aktuellen Ordner anzeigen
- pwd - Zeigt das aktuelle Arbeitsverzeichnis an
- mkdir NewFolder - Erstellt ein neues Verzeichnis mit dem Namen "NewFolder".
- rm NewFile - Löscht eine Datei namens "NewFile"
- rm -f NewFile - Erzwungenes Löschen einer Datei namens "NewFile"
- rm -r NewFolder – löscht rekursiv das Verzeichnis mit dem Namen „NewFolder“
rm -rf NewFolder - Löscht zwangsweise ein Verzeichnis namens "NewFolder" rekursiv
cp oldfile1 newfile2 - Kopiert den Inhalt von oldfile1 nach newfile2
cp -r olddir1 newdir2 Kopiert das Verzeichnis "olddir1" rekursiv nach "newdir2". Dir2 wird erstellt, wenn es nicht existiert.
mv oldfile1 newfile2 - Benennt "oldfile1" in "newfile2" um.
ln -s /etc/log/file logfile – Erstellt eine Verknüpfung zu einer Datei
touch newfile - Erstellt eine leere Datei namens newfile
cat > newfile - Platziert STDIN in newfile
more newfile - Zeigt den Inhalt von newfile in Teilen an
head newfile - Zeigt die ersten 10 Zeilen von newfile an
tail newfile - Gibt die letzten 10 Zeilen von newfile aus
gpg -c newfile - Verschlüsselt newfile im gpg-Format mit einem Passwort und speichert es im selben Verzeichnis.
gpg newfile.gpg - Entschlüsselt eine gpg-Datei
wc newfile - Zeigt die Anzahl der Bytes, Wörter und Zeilen der neuen Datei an.