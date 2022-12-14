# Projekt-Dokumentation

Blobfisch

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Workshop anmelde Programm

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ | Beschreibung                       |
| ---- | --------------- |-----| ---------------------------------- |
|   1  |       Muss      | FA  | Als ein Benutzer, möchte ich dass das Programm am Anfang fragt ob man ein neues Konto erstellen möchte damit neue Benutzer eins schnell erstellen können|
|   2  |       Muss      | FA  | Als ein Benutzer, möchte ich dass das Programm ein Login hat damit ich nachschauen kann welchen Workshop ich bekommen habe |
|   3  |       Muss      | FA  | Als ein Benutzer, möchte ich dass das Programm die Workshop einschreibungen Fair einteilt werden |
|   4  |       Muss      | FA  | Als ein Benutzer, möchte ich dass das Programm erkennt welche Workshops welche Priorität haben |
|   5  |       Muss      | FA  | Als ein Benutzer, möchte ich dass das Programm mir mitteilt bei welchem Workshop ich zugeteilt wurde sobald es entschieden ist |
|   6  |       Kann      |Quali| Als ein Benutzer, möchte ich dass das Programm mich beim Start begrüsst|
|   7  |       Kann      |Quali| Als ein Benutzer, möchte ich dass das Programm mir die Beliebtesten Workshops anzeigt damit ich rückicht darauf nehmen kann |
|   8  |       Kann      |Quali| Als ein Benutzer, möchte ich dass das Programm zusatzinformationen zu den Workshop hat |
|   9  |       Kann      |Quali| Als ein Benutzer, möchte ich dass das Programm ein Befehl hat mit welchem ich Kontaktdaten erfahre um Feedback zu hinterlassen |
|  10  |       Kann      |Quali| Als ein Benutzer, möchte ich dass das Programm nach dem auswählen der Workshops eine Tempöräre zuordnung anzeigt |
|  11  |       Kann      |Quali| Als ein Benutzer, möchte ich dass das Programm ansprechend aussieht |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet, Kontoerstellungsfrage gestellt | Ja      | Bitte geben sie ihr Benutzername ein |
| 2.1  | Programm gestartet, Kontoerstellungsfrage gestellt | Nein    | Bitte logen Sie sich ein |
| 3.1  | Programm gestartet, Eingeloggt | Workshop prioritäten gesetzt         | Ihre Priöritäten sind: 1. ...  2. ... 3. ...|
| 4.1  | Programm gestartet | Einloggen         | Sie wurdem den Workshop ... zugeteilt|
| 5.1  |Programm gestartet, Eingeloggt| Workshop auswahl         |Folgende Workshops stehen zur Auswahl; ..., ..., ..., diese drei wurden bis jetzt am meisten gewählt.|
| 6.1  |Programm gestartet, Eingeloggt|Workshop auswählen| In diesem Workshop geht es um...                    |
| 7.1  |Programm gestartet, Eingeloggt|feedback|Hier können die uns kontaktieren: ...|
| 8.1  | Programm gestartet, Eingeloggt |Workshopauswahl abschliessen| Sie wurdem temporär dem Workshop ... zugeteilt|

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |Lukas| Konto kann erstellt werden |    45min      |
| 2:A  |       |Lukas| Benutzer kann sich bei einem bestehenden Konto einloggen|    45min     |
| 3.A  |       |Mirhan| Workshop werden angezeigt und können ausgewählt werden|    60min    |
| 4.A  |       |Brandon| Workshops werden fair unter den Anmeldungen ausgeteilt|    90min     |
| 5.A  |       |Christian| Finale zuteilung erfolgt direkt nach dem Entscheid|      45min    |
| 6.A  |       |Lukas| Programm begrüsst einem beim Start|   30min     |
| 7.A  |       |Mirhan| Das Programm zeigt die Beliebtesten Workshops an |   90min   |
| 8.A  |       |Brandon| Das Programm kann bei Interesse zusatzinformationen zu einem bestimmten Workshop angeben |   45min     |
| 9.A  |       |Christian| Es gibt einen Feedback befehl|  30min    |
|10.A  |       |Brandon| Temporäre zuordnung der Workshops |   90min     |
|11.A  |       |Christian| Programm schön darstellen |  90min |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
