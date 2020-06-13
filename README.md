# EasyScanAndAction
Aktionen/Aufgaben/Informationen per QR-Code übertragen und ausführen

## In aller Kürze:
Mittels einer App für Android und iOS können QR-Codes erstellt und gescannt werden.
Die enthaltenen Informationen triggern auf der scannenden Seite halb-/automatische Aktionen, wie zum Beispiel den Versand einer vorformatierten E-Mail an einen übertragenenen Empfänger.
Mit der App können sowohl QR-Codes erstellt, als auch gelesen und ausgeführt werden.

Entwickelt werden soll die App in ihrer Basisfunktionalität im Oldenburger Civic Data Lab Hackathon [1]. Das Protokoll, also welche Daten/Aktionen im QR-Code ausgetauscht werden können ist noch nicht festgelegt und gerade dafür bietet sich ein Hackathon mit vielen Teilnehmern aus verschiedensten Fachrichtungen und mit unterschiedlichsten Interessen an um einen schönen Strauß an Anwendungsmöglichkeiten zu bekommen.

## Szenario 1:
Aktuell müssen - zum Beispiel in Restaurants und bei Frisören (Geschäft) - zur Corona-Kontaktnachverfolgung bei jedem Besuch die Kontakdaten des Kunden aufgenommen für wenige Wochen aufbewahrt werden.
Bis auf kleine Unterschiede im Umfang der erhobenen Daten findet immer der gleiche Vorgang statt.
Mit der App kann dieser Vorgang sowohl für den Kunden, als auch für das Geschäft wesentlich komfortabler gestaltet werden:
Das Geschäft erstellt mit der App einen QR Code der folgendes enthält:
- Eine AktionsId (Datenabfragen und Senden)
- Umfang der gewünschten Kontaktdaten
- E-Mailadresse an die die Kontaktdaten geschickt werden sollen
Der QR-Code wird als PDF erstellt, ausgedruckt und für den Kunden scannbar am Eingangstresen oder auf den Tischen angebracht.

Als Kunde kann der QR-Code dann mit dieser App gescannt werden. Daraufhin wird die AktionsID interpretiert und die gewünschten Daten in einem Formular abgefragt. Nur beim ersten Mal müssen die Daten dann noch eingegeben werden. Im nächsten Geschäft oder beim zweiten besucht werden die Daten dann schon automatisch vorausgefüllt.
Mit einem Klick auf "Absenden" wird dann eine entsprechend formatierte und gefüllte Mail an die übergebene E-Mailadresse gesendet.

Papier ist damit nicht mehr nötig und die Datenerfassung geht wesentlich schneller und einfacher.

[1] https://hackathon.kreativitaet-trifft-technik.de/

[2] Digitale Lernlabore - Urban Data Labs und Civic Data Labs für die Smart City. Linkssammlung - https://realtime.fyi/articles/panicroomplus/digitale-lernlabore-urban-data-labs-und-civic-data-labs-fuer-die-smart-city-linkssammlung


