This Github project is used to work on the eCH-0260 data exchange standard for vocational education and training and provides the latest XML schemas for eCH-0260 and for sedex messages.

The currently valid and officially published version of eCH-0260 can be found at https://ech.ch/de/ech/ech-0260/2.0.0.

Further information on the introduction of the new data exchange processes ("HAKA-processes") can be found at https://www.sdbb.ch/datenmanagement/projekte/da-bbi

Publizierte Versionen: 
- eCH-0260 Version 2.0 --> TBD
- DAK - Datenaustauschkonzept Version 3.0 --> TBD
- SOLL - Soll-Datenaustauschprozesse Version 3.0 --> TBD


Release notes for version 2.2

| Issue    | Beschreibung | Erledigt | Offen |
| -------- | ------- | ------- |------- |
| #66  |  | - | - |
| #65  | "Auslöser" für VA1 nicht vollständig | DAK 4.1.2.5 in Version 3.2 | - |
| #64  | Falsches Format apprenticeshipPlaceOptions in XSD | XSD angepasst | - |
| #63  | coverageOf... dürfen nicht boolean sein | XSD, eCH-0260 Kap. 4.11 und 5.10 | - |
| #62  | Zu welchem Zweck dient "noteControl" im examAssignmentType | Keine, s.Nr. #  | - |
| #61  | applicationContact auf apprenticeshipPlaceType: Korrekt oder eher VetAccreditationType | - | - |
| #60  | Verwendung countryType aus eCH-0010 | eCH-0260 Kap. 4.4 und 4.5 sowie 2.13 | - |
| #59  | examAssignmnetType: Kanton doppelt vorhanden | XSD und eCH-0260 Kap. 3.6 | - |
| #58  | Tippfehler representativeType XSD | XSD | - |
| #57  | Wie kann übermittelt werden, dass trotz Auflösung die Schule noch besucht werden kann? | XSD (Kommentar), eCH-0260 Kap. 3.11 | - |
| #56  | Frage zu Übernahme der Schulkosten | wurde gelöst mit #63 | - |
| #55  | Welche Zweck hat der Wert 4 (BMS) des Elements noteControl | XSD, eCH-0260 4.23 und 4.25 | - |
| #54  | Welche Prüfungskommission wird im examAssignmentType geliefert? | XSD Version 2.2 | - |
| #53  | Best Practice: Meldungen pro sedex-Datenlieferung | Keine Anpassung | - |
| #52  | Wie werden Mutationen von Prüfungszuweisungen übermittelt? | Keine Anpassung | - |
| #51  | Prüfung von Duplikaten im Schema | Keine Anpassung | - |
| #50  | Schreibfehler im VETaccreditationType, eCH-0260 Version 2.1.0  | eCH-0260 | - |
| #49  | Wie wird ein Klassenwechsel übermittelt? | DAK 4.4.2.2 | - |
| #48  | Wird MT7 auch interkantonal verwendet oder nur für die Meldung an Prüfungsorganisationen? | DAK 4.3.2.5 | - |
| #47  | Wie kann in einer Erstlieferung eine Repetition übermittelt werden? | DAK keine Anpassung (nur Ebene TV erwähnt), XSD, eCH-0260 Kap. 3.6 und 4.11 rep.With... aufnehmen | -|
| #46  | Zwei LV mit gleicher LV-Nr. | DAK 3.9.2 und 4.7.2.1/3/5 | - |
| #45  | Inconsistent naming | - | XSD, eCH-0260 |
| #44  | Umgang mit validTo im "VetAccreditationAndTrainerType" | XSD, eCH-0260, s. #41 | - |
| #43  | Umgang mit LV-Auflösungen | SOLL 5.3.1, DAK 4.7.2.1/3/5/8 | eCH-0260: M09 streichen |
| #42  | Umgang mit Schulbesuchsdaten | keine Anpassung | - |
| #41  | Umgang mit Berufsbildnern | - | XSD, eCH-0260 |
| #40  | Geschlecht bei gesetzlichen Vertretern nicht obligatorisch | - | ev. DAK -> Vorschlag: eCH-0260 Kapitel 2.4|
| #39  | Lieferung AHV-Nummer für Lernende/Berufsbildner | XSD, eCH-0260 4.4 | XSD, eCH-0260 4.46 |
| #37  | from - to-Datum ergänzen bei Meldungen aus zentraler Datenbank | DAK 4.3.2 / 4.4.2 / 4.5.2, XSD, eCH-0260 Kap. 3.14 und 3.15 | - |
| #36  | Mehrere Mutationsgründe übermitteln | Soll-Konzept Kapitel 5.3.1, Übernahme Felder pro Mutationsgrund (s. Excel Mutatiosngründe) in DAK, neuer Anhang A.2 / 4.7.2 | - |



