# w231-doku

Diese Doku widmet sich dem Fach Datenschutz und Sicherheit, welches hiermit Dokumentiert wurde.


--------------------------------------
Inhaltsverzeichnis

[05.9.23 | Allgemeinnutzung Git](https://github.com/MaxHD00/w231-doku/tree/main#allgemeinnutzung-git)

[12.9.23 | Backups](https://github.com/MaxHD00/w231-doku/tree/main#backups)

[12.9.23 | Datensicherungsziele, Datenkompression...](https://github.com/MaxHD00/w231-doku/tree/main#datensicherungsziele-datenkompression-mit-den-unterthemen)

[19.9.23 | Prüfung & Backupvorgehen](https://github.com/MaxHD00/w231-doku/tree/main#pr%C3%BCfung-wie-auch-weiter%C3%BCbung-von-backupvorgehen)

[26.9.23 | Faktor-Auth., Authentisierung und co.](https://github.com/MaxHD00/w231-doku/tree/main#faktor-auth-authentisierung-authentifizierung-und-autorisierung)

[26.9.23 | Passwortmanager](https://github.com/MaxHD00/w231-doku/tree/main#passwortmanager)

[03.10.23 | Verschlüsselungsmethoden](https://github.com/MaxHD00/w231-doku/tree/main#verschl%C3%BCsselungsmethoden)

[24.10.23 | Problematik von Datenlöschungen](https://github.com/MaxHD00/w231-doku/tree/main#problematik-von-datenl%C3%B6schungen)

[31.10.23 | Lizenzmodelle](https://github.com/MaxHD00/w231-doku/tree/main#lizenzmodelle)

[07.11.23 | Abschluss](https://github.com/MaxHD00/w231-doku/tree/main#abschluss)

--------------------------------------



_5 September 2023_

### Allgemeinnutzung Git
hierzu sind die Grundbefehle git <push/pull/add/commit> wichtig.
Zugleich das lesen von Datenschutzgesetzen der DSG.

--------------------------------------
_12 September 2023_

### Backups

Wie zu Sichern ist, wie oft zu Sichern ist und wo zu Sichern ist.
Spiegelung einer Festplatte(Vollsicherung) sowie inkrementelle oder differenzielle Datensicherung.



### Datensicherungsziele, Datenkompression mit den Unterthemen

Geräte, welche als Backup-Ziel verwendet werden. Dazu schrieben wir die üblichen Speichenmedien wie die Optischen(CD,DVD),
die Magnetischen(HDD, Sicherungsbänder) oder auch weitere wie Flash(USB) oder Cloudspeicher.

Komplessionsverfahren, welche heute noch genutzt werden. Dazu schrieben wir konkret die Methoden wie LZMA2, LZMA, PPMd oder BZip2. Diese werden über Formate wie zip, rar oder 7z verwaltet. Unterschiede wie das LZMA2 im gegensatz zu LZMA mehrere Kerne nutzt ginge hier zu tief ins Detail.

Als letztes wurde gefragt wieso denn Datenkompression so wichtig sei insbedondere bei Image-Backups. Hierzu sei gesagt, dass
Kompremierte Dateien nach zusammenfassung wieder entkompremmiert werden müssten. Das braucht Zeit. Diese zeit spielt hier aber weniger eine Rolle als die vergleinerung von Dateien. Insbesondere bei backups, welche auch ziemlich gross werden können. Demnach bei Image-Backups sind die Vorteile einer Kompression viel wichtiger als die Nachteile.

--------------------------------------
_19 September 2023_
### Prüfung wie auch weiterübung von Backupvorgehen
[Backup](backup.md)


--------------------------------------
_26 September 2023_
### Faktor-Auth., Authentisierung, Authentifizierung und Autorisierung

[Faktor-Authentisierung](Faktor-Authentisierung.md)

[Authentisierung-Authentifizierung-Autorisierung](Authentisierung-Authentifizierung-Autorisierung.md)


### Passwortmanager


Desktop:


![Keypass Desktop](https://github.com/MaxHD00/w231-doku/assets/31143468/087a955e-aaed-4e8a-8ec7-a29d7d8671dd)


Handy:


![Keypass Handy](https://github.com/MaxHD00/w231-doku/assets/31143468/a6bc4792-248f-44f0-8769-d27d2d7fd103)

--------------------------------------
_3 Oktober 2023_
### Verschlüsselungsmethoden
Cäsar methode:
Buchstaben werden um x geshiftet.
Hallo -> Code: 3->  -> Kdqqr
Vigenere methode:
Buchstaben werden zu einem zeichencode addiert.
Hallo -> Code: 2345 -> Jdrsq

--------------------------------------
_24 Oktober 2023_
### Problematik von Datenlöschungen
Jede Datei welche gelöscht wird, wird meist nur gelöscht wenn man diese Datei etwa
nicht mehr benötigt oder diese Datei mehrmals Existiert.
Aber vor allem beim zweiten herscht das Problem, dass man vertrauen muss, dass
die andere Kopie funktionsfähig ist oder überhaupt existiert.
Andererseits kann auch eine starke unübersichtlichkeit entstehen, sollten gewisse Daten
mehrmals existieren. Vor allem wenn manche daten überholt wurden und nicht mehr auf dem
Aktuellen Stand sind. Es kann auch passieren, dass wir Daten löschen, weil wir denken wir benötigen es nicht mehr.
Und dann noch 3 Monate später ärgert man sich aufgrund des Löschens wohl doch noch so unwichten Daten.

[Impressum-Disclaimer-AGB](Impressum-Disclaimer-AGB.md)

--------------------------------------
_31.Oktober.2023_
### Lizenzmodelle
[Lizenzmodelle](Lizenzmodelle.md)

--------------------------------------
_7 November 2023_
### Abschluss
Das Dossier wurde hier noch ein wenig korrigiert und dann abgeschlossen.