# EasyScanAndAction fork 
Kontakte zeitsparend anbahnen und ad-hoc Aktionsnetzwerke knüpfen

## In aller Kürze:
Dies ist ein Fork der angestrebten EasyScanAndAction-Lösung [4]. Schwerpunkt des Forks ist die Kontaktanbahnung, Vernetzung von Kontakten und die Befähigung der vernetzten Personen aktiv zu werden, bestimmte Aktionen auszulösen. Die Kontaktanbahnung, Vernetzung mittels eines QR-Codes wie in der angestrebten EasyScanAndAction-Lösung ist eine in bestimmten Szenarien vorteilhafte Kontaktmöglichkeit.

Das Oldenburger Civic Data Lab Hackathon [1] bietet die Möglichkeit mit vielen Teilnehmern aus verschiedensten Fachrichtungen und mit unterschiedlichsten Interessen denkbare Anwendungsmöglichkeiten des EasyScanAndAction forks auszuloten.

## Szenario 1 - eMail-Übermittlung:
Aktuell müssen - zum Beispiel in Restaurants und bei Frisören (Geschäft) - zur Corona-Kontaktnachverfolgung bei jedem Besuch die Kontakdaten des Kunden aufgenommen für wenige Wochen aufbewahrt werden.
Bis auf kleine Unterschiede im Umfang der erhobenen Daten findet immer der gleiche Vorgang statt.
Mit der App kann dieser Vorgang sowohl für den Kunden, als auch für das Geschäft wesentlich komfortabler gestaltet werden:
Das Geschäft erstellt mit der App einen QR Code der folgendes enthält:
- Eine AktionsId (Datenabfragen und Senden)
- Umfang der gewünschten Kontaktdaten
- E-Mailadresse an die die Kontaktdaten geschickt werden sollen
Der QR-Code wird als PDF erstellt, ausgedruckt und für den Kunden scannbar am Eingangstresen oder auf den Tischen angebracht.

Als Kunde kann der QR-Code dann mit der EasyScanAndAction App von der Website des Geschäfts oder im Geschäft selbst gescannt werden. Daraufhin wird die AktionsID interpretiert und die gewünschten Daten in einem Formular abgefragt. Nur beim ersten Mal müssen die Daten dann noch eingegeben werden. Im nächsten Geschäft oder beim zweiten besucht werden die Daten dann schon automatisch vorausgefüllt.
Mit einem Klick auf "Absenden" wird dann eine entsprechend formatierte und gefüllte Mail an die übergebene E-Mailadresse gesendet.

Papier ist damit nicht mehr nötig und die Datenerfassung geht wesentlich schneller und einfacher.

## Szenario 2 QR-Übermittlung:
- Besucher:innen eines Lokals oder Frisörs generieren einen QR-Code mit den in der Vorlage Gästeregistrierung [5] vorgesehenen persönlichen Daten 
- die Daten werden per QR-Code wird in die Erfassungslösung der Gaststäte eingelesen
- die Daten werden an das Gesundheitsamt übermittelt - s. Anforderungen in [6]

## Szenario 3 - Bezahlung:
- den Besucher:innen wird vom Lokalbetreiber oder Frisör ein QR-Code mit der Rechnung präsentiert
- Besucher:innen lesen mit der EasyScanAndAction App den Code ein, prüfen die Rechnung 
-  Besucher:innen generieren einen QR-Code mit einer "Bezahlen"-Aktion (der Funktionsumfang der "Bezahlen"-Aktion muss noch definiert werden)
- vlt. kann das "Szenario 3 - Bezahlung" Feature für die Erfassung von Statistiken: a) Wie viele Besucher:innen haben die Lokale bzw. Frisöre? b) Wie viele Besucher:innen unterstützen die Aktion "Ich kaufe in Oldenburg!" genutzt werden?

## Quellenverzeichnis
[1] Oldenburger Civic Data Lab Hackathon - https://hackathon.kreativitaet-trifft-technik.de/

[2] Digitale Lernlabore - Urban Data Labs und Civic Data Labs für die Smart City. Linkssammlung - https://realtime.fyi/articles/panicroomplus/digitale-lernlabore-urban-data-labs-und-civic-data-labs-fuer-die-smart-city-linkssammlung

[3] Ideen In Der Corona-Krise: Kontaktloses Einkaufen im Ammerland leicht gemacht, 01.04.2020 - https://www.nwzonline.de/plus-ammerland/ammerland-edewecht-ideen-in-der-corona-krise-kontaktloses-einkaufen-im-ammerland-leicht-gemacht_a_50,7,3394774699.html

[4] EasyScanAndAction - https://github.com/jw23578/EasyScanAndAction

[5] Vorlage Gästeregistrierung - https://www.dehoga-niedersachsen.de/branchenthemen/corona-krise/

[6]  Anforderungen Datenschutz bei der Gästeregistrierung für die Gaststätten in Niedersachsen - [5]


[7] In Oldenburg: Lokal einkaufen – jetzt erst recht! - https://www.oldenburg.de/startseite/wirtschaft/wirtschaftsfoerderung/corona-lokal-einkaufen-uebersichts-und-unterstuetzungsportale.html

[8] Wiedereintritt unter Bedingungen der Corona-Krise. Gastronomie. Stand: 28.05.2020 - https://www.dehoga-niedersachsen.de/fileadmin/04_Branchenthemen/Wiedereintritt_Gastronomie_28052020_inklAnlagen.pdf

[9] Beschreibung der Prozessorganisation und der Infrastruktur bei der Rufnummerportierung - https://administrator.de/forum/rufnummernmitnahme-portierung-beschleunigen-528428.html#comment-1414820

[10] Verordnung  zur Änderung der Niedersächsischen Verordnung über infektionsschützende  Maßnahmen gegen die Ausbreitung des Corona-Virus vom 5. Juni 2020 - https://www.oldenburg.de/fileadmin/oldenburg/Benutzer/PDF/01/Corona-VO_05-06-2020.pdf
