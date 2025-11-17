Unterverband administrieren
======================

In diesem Kapitel werden Funktionen erläutert, um Unterverbände zu verwalten. Diese sind nur für Personen sichtbar oder
zugänglich, welche die entsprechende Gruppenzugehörigkeit und Rolle besitzen.

## Neue Mitglieder erfassen

Um ein neues Mitglied zu erfassen gibt es zwei Möglichkeiten.
Entweder kann das allgemeine Neuregistrierungsformular vom Mitglied selbst, oder auch von einem Verantwortlichen des Untervarbands ausgefüllt werden, oder eine Person mit der Rolle `Administration` in einem Unterverband kann neue Mitglieder direkt in der entsprechenden Mitgliedergruppe hinzufügen.

### Neuregistrierungsformular

Über das [Neuregistrierungsformular](https://db.ejv.ch/de/groups/5/self_registration) vom EJV können beliebige Personen neu registriert werden.
Dies kann entweder vom Neumittglied selbst ausgefüllt werden, oder jemand aus der Verwaltung kann dies auch im Namen des Neumitglieds ausfüllen.

In einem ersten Schritt muss hier nun die Emailadresse der neu zu registrierenden Person eingegeben werden.
Damit prüft Hitobito ob es für diese Person bereits einen Eintrag gibt, oder ob tatsächlich ein neuer Eintrag angelegt werden muss.

Ist die Emailadresse bereits vergeben, kann das Mitglied selbst sich das Passwort zurücksetzen lassen und erhält dadurch eine Email mit welcher es sich einloggen kann. Eine Neuregistration ist in diesem Fall nicht notwendig.
Ist die Emailadresse noch nicht vergeben, kommt man zum zweiten Schritt.
Hier können nun die Personendaten ausgefüllt und das Formular anschliessend abgesendet werden.
Ein Administrator des Eidgenössischen Jodlerverbands wird anschliessend das Neumitglied in die korrekte Gruppe einteilen.

![image](images/Selbstregistrierung_Neumitglied.png)

### Neumitglied erfassen

Personen mit der Rolle `Administration` können in ihrem eigenen Unterverein neue Personen erfassen.

Dazu muss zuerst im der Navigation links in die korrekte Gruppe navigiert werden. Dort kann unter dem Menupunkt Personen ein neues Mitglied für diesen Verein erfasst werden.
![image](images/mitglied_erfassen1.png)

Damit landet man auf der Maske "Person hinzufügen" zuerst in der Ansicht um eine bestehende Person zu suchen.
Zuerst soll die Person über das Suchfeld mit Namen gesucht werden `1`.

Anhand des Namens wird eine treffende Auswahl der bereits vorhandenen
Mitgliedern mit Wohnort und Jahrgang angezeigt. Falls die gesuchte
Person existiert, ist sie `2`

  - der gewünschten Gruppe,
  - mit entsprechender Rolle,
  - allenfalls einer weiteren Bezeichnung
  - und dem Eintrittsdatum zuzuweisen.
![image](images/mitglied_erfassen2.png)

Anschliessend empfiehlt es sich, die Angaben der Person zu prüfen und
gegebenenfalls anzupassen. Hat das Mitglied noch keine
Haupt-E-Mailadresse ist diese für den Login auf die Datenbank
einzusetzen.

Wenn bei der Eingabe des Namens keine Auswahl angezeigt wird, kann
direkt über die Tastatur **Enter** gedrückt, oder auf die Funktion "Neumitglied erfassen" `3` geklickt werden und man gelangt in
die Maske für **Neue Person erfassen**.

Hier müssen mindestens die mit einem Stern markierten Felder ausgefüllt und eine Rolle ausgewählt werden.
![image](images/mitglied_erfassen3.png)

Mit `Speichern` wird die Person mit der entsprechenden Rolle angelegt.
Im Anschluss landet man auf dem Profil des Neumitglieds und kann bei Bedarf noch weitere Daten zur Person erfassen.
![image](images/mitglied_erfassen4.png)

---
## Adressmutationen

Ist ein Mitglied umgezogen und muss die Adresse geändert werden, so muss zuerst auf die Person navigiert werden.
Dies kann über die globale suche, oder über die Navigation links geschehen.
Mit `Bearbeiten` können anschliessend alle Personendaten angepasst werden.

Werden Adressmutationen noch im **Jahr 2025** vorgenommen, muss der Person anschliessend das Tag `Som-Nov` gegeben werden.
![image](images/Som-Nov.png)

---
## Rollenmutationen

### Rolle innerhalb einer Gruppe ändern
Um einer Person eine andere Rolle innerhalb einer Gruppe zu geben, gibt es mehrere Möglichkeiten.
Am einfachsten kann man dies direkt auf der Personenübersichtder Gruppe vornehmen. 

Dazu klickt man `1` auf Bearbeiten, wählt dann `2` die neue Rolle aus und speichert diese `3`.
![image](images/roles1.png)
Dadurch wird die alte Rolle per heute beendet. Die neue Rolle hat das gleiche Startdatum wie die bisherige Rolle hatte.

Möchte man ein anderes Startdatum eingeben können, so kann man die Rolle auch direkt auf der Personenübersicht ändern. 
Dazu navigiert man zuerst auf die entsprechende Person und bearbeitet die Rolle direkt auf dieser Ansicht.
![image](images/roles2.png)
Dabei gelangt man auf eine neue Ansicht in der man `1` die neue Gruppe und Rolle auswählen kann. Anschliessend kann man ein Start und bei Bedarf Enddatum für die Rolle setzen `2`.
Rechts wird einem dabei angezeigt, welche Rechte die neue Rolle haben wird `3`.
Mit Speichern wird dies geändert. Die alte Rolle wird per heute terminiert.
![image](images/roles3.png)

### Neue Rolle in der gleichen Gruppe hinzufügen
Will man einer Person eine neue, zusätzliche Rolle in einer Gruppe geben, navigiert man zuerst auf die Person.
Über den Button Rolle hinzufügen `1` gelangt man auf die Maske um eineneue Rolle anzulegen.
![image](images/roles4.png)
Hier wählt man  `1` die neue Gruppe und Rolle auswählen kann. Anschliessend kann man ein Start und bei Bedarf Enddatum für die Rolle setzen `2`.
Rechts wird einem dabei angezeigt, welche Rechte die neue Rolle haben wird `3`.
Mit Speichern erhält die Person die zusätzliche Rolle. Ist das Startdatum der Rolle in der Zukunft, so ist dies nicht per sofort auf der Person, sondern nur im Verlauf der Person ersichtlich.
![image](images/roles5.png)

### Neue Rolle in neuer Gruppe
Will man einer Person eine neue Rolle in einer komplett anderen Gruppe geben, so muss man zuerst links in der Übersicht auf die entsprechende Gruppe navigieren `1`. 
Anschliessend kann man im Personen-Tab `2` dieser Gruppe "Person hinzufügen" `3` auswählen.
![image](images/roles6.png)
Hier kann man nun die bestehende Person suchen. Dazu gibt man den Namen der Person welche die neue Rolle erhalten soll im Suchfeld `1`ein und wählt die korrekte Person aus.
Anschliessend wählt man auch hier die entsprechende Rolle aus `2` und sieht rechts was die Rolle für Rechte hat. 
Letztlich wählt man Eintritts- und allenfalls Austrittsdatum an `3` und speichert.
![image](images/roles7.png)

---
## Mitglieder löschen

Personen können durch die Administration eines Unterverbandes nicht komplett gelöscht werden.
Ist eine Person nicht länger Mitglied in einem Verein, wird stattdessen die Rolle in der entsprechenden Gruppe gelöscht.
Dazu navigiert man zuerst auf die Person. Im Info Tab rechts sind alle aktiven Rollen dieser Person ersichtlich.
Mit dem Papierkorb kann nun die Rolleder Person beendet werden.
![image](images/mitglied_loeschen1.png)
Hat die Person noch weitere Rollen in anderen Gruppen, so ist sie dort noch immer ersichtlich.
War dies die letzte Rolle einer Person, so erscheint die Person nur noch in der Gruppe `Ohne Rollen`.
Personen in der Gruppe `Ohne Rollen` können nur von Administratoren vom EJV endgültig gelöscht werden.

---
## Mitgliederlisten erstellen und exportieren

### Mitgliederliste einer Gruppe exportieren.
Will man eine Liste sämtlicher Personen in einer Gruppe exportieren, kann man dies einfach in der entsprechenden Gruppe `1` auf der Personenübersicht `2` über den Button "Export" `3` ausführen.

Hier hat man die Auswahl zwischen verschiedenen Exportformaten.
Bei CSV und Excel kann anschliessend ausgewählt werden, ob man die aktuell angezeigten Spalten, eine einfache Adressliste, alle Angaben der Personen oder eine Haushaltsliste in der Personen die im gleichen Haushalt wohnen zusammengefasst werden exportieren will.
![image](images/export1.png)
Bei sehr grossen Listen kann dies eine gewisse Zeit dauern. 
Der Export wird anschliessend direkt heruntergeladen und auf dem eigenen PC gespeichert.

### Personenliste  erstellen und exportieren
Will man eine Liste von Personen aufrufen welche nicht alle in der gleichen Gruppe sind, jedoch sonnst gewisse gemeinsame Attribute haben, so kann dies über den Personenfilter gemacht werden.
Dazu wird zuerst links auf die Gruppe des Unterverbands navigiert. Hier kann im Tab "Personen" unter "Weitere Ansichten" entweder ein zuvor gespeicherter Filter ausgewählt, oder ein Neuer Filter erstellt werden.
![image](images/export2.png)

![image](images/export3.png)



---
## Abos erstellen und verwalten
Hinter den Abos versteckt sich ein mächtiger Personenfilter welcher vielseitig einsetzbar ist.
Mögliche Einsatzgebiete für Abos sind Exporte von Personenlisten, Email-Verteiler, Listen für den Physikalischen Zeitschriftenversand, Rechnungsversand und mehr.

Von Persoenen mit Leserechten auf einer Gruppe, können für diese und darunterliegende Gruppen Abos erstellt und verwaltet werden.
Dafür geht man auf der obersten Gruppen von welcher man Personen in diesem Abo inkludieren möchte auf den Tab Abos, und wählt "Abo erstelltn"
Will man also Beispielsweise leute der ganzen SChweiz inkludieren, muss das Abo auf dem Dachverband erstellt werden. Will man nur Personen von BKJV inkludieren, kann man das abo auf dieser Gruppe erstellen. Man kann abera uch Abos für Lokalgruppen auf einer einzelnen Jodlergruppe erstellen und dann nur Personen dieser Gruppe inkludieren. 

Im Tab Allgemein gibt es die folgenden Einstellungsmöglichkeiten:
- Name: Jedes Abo braucht einen einzigartigen Namen. Dieser wird auch in den Personenprofilen aller dazugehörigen Personen angezeigt, sollte also möglichst eindeutig sein.
- Beschreibung: Optional kann dem Abo eine detailliertere Beschreibung gegeben werden, wofür dieses Abonement verwendet wird.
- Herausgeber: Optionales Feld, welches beim Auswählen neuer Abonements angezeigt wird und beim einordnen des Abos hilfreich sein kann.
- Selbst an/abmelden: Diese Auswahl gibt an, ob sich Personen selbst für dieses Abo an oder abmelden können. Es kann auch ausgewählt werden, ob sich nur die Personen welche ausgewählt werden anmelden dürfen, oder alle Personen in der Hitobito Datenbank.
- Personen sind Standartmässig: Hat man beim oberen Punkt eine der beiden hinteren Optionen ausgewählt, erscheint diese Auswahlmöglichkeit. Angemeldet(opt-out) bedeutet dass die definierten Personen standartmässig alle angemeldet sind, sich jedoch manuell abmelden können. Abgemeldet (opt-out) Bedeutet dass standartmässig keine Personen in dem Abo vorhanden sind, die definierten Personen sich aber manuell zu dem Abo anmelden können.

Im Tab Mailing-Liste (Email) gibt es die folgenden Einstellungsmöglichkeiten:
- Mailinglisten Adresse: Versendet man Emails über dieses Abo so ist dies die Absenderadresse welche die betreffenden Personen sehen.
- Zusätzlicher Absender: Müssen einzelne, weitere Personen als nur Personen mit Schreibrechte auf dieser Gruppe auch über dieses Abo Emails versenden können, können die entsprechenden Emailadressen hier eingetragen werden.
- Bevorzugte E-Mail-Labels: Möchte man den Versand bevorzugt an bestimmte Emailadressen machen, kann man dies hier definieren. Es kann auch definiert werden, dass der Versand nur an die Haupt E-Mail_Adresse erfolgt, unabhängig davon ob noch weitere Versandadressen auf den Personen vorhanden sind.
- Abonnenten dürfen auf die Mailingliste schreiben: Ist dieser Punkt angewählt, dürfen alle Empfänger der Abo-Liste auch selbst auf diese schreiben. Bei vielen Empfänger wird davon eher abgeraten.
- Beliebige Absender/-innen dürfen auf die Mailingliste schreiben: Ist dieser Punkta ngewählt dürfen beliebige Absender an den Abo-Verteiler schreiben. Ausser bei sehr spezifischen Usecases wird davon klar abgeraten.
- E-Mail mit Bestätigung an Absender schicken: Ist dies angewählt, erhält der Absender einer Email eine Bestätigung nachdem alle Emails versendet wurden.

Im Tab MailChimp gibt es Einstellungsmöglichkeiten falls die Adresslisten dieses Abonements mit einem bestehenden Mailchimp Konto Synchronisiert werden sollen.
- Sowohl die MailChimp Listen-ID wie auch der MailChimp API-Schlüssel bekommt man direkt von Mailchimp.
- Jede MailChimp Liste kann nur auf genau ein Abo in Hitobito gemappt werden.







---
## Anlässe erstellen und verwalten

\-tbd-

---
## Kurse erstellen und verwalten

\-tbd-

---
## Rechnungen

\-tbd-

---
## SUISA

\-tbd-


---
## Modul Hilfe

### Hilfetext

Die Texte können in den drei Landessprachen Deutsch, Französisch und
Italienisch erfasst werden. Um einen Text zu übersetzen, muss zuerst die
Sprache (unten links) geändert werden und dann der Text übersetzt
werden.

<div class="attention">
Die Hilfetexte sind global (Stufe hitobito\!)
</div>
