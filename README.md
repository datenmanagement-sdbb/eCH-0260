This Github project is used to work on the eCH-0260 data exchange standard for vocational education and training and provides the latest XML schemas for eCH-0260 and for sedex messages.

The currently valid and officially published version of eCH-0260 can be found at https://ech.ch/de/ech/ech-0260/2.0.0.

Further information on the introduction of the new data exchange processes ("HAKA-processes") can be found at https://www.sdbb.ch/datenmanagement/projekte/da-bbi

Publizierte Versionen: 
- eCH-0260 Version 2.0
- DAK - Datenaustauschkonzept Version 3.0
- SOLL - Soll-Datenaustauschprozesse Version 3.0


Release notes for version 2.1

| Issue    | Beschreibung | Erledigt | Offen |
| -------- | ------- | ------- |------- |
| #31  | Anpassung regexp in schoolId (Punkte erlauben) | - | XSD, eCH-0260, Kap. 2.14  |
| #30  | Wert 0 streichen in Steuerfeld Noten | XSD, eCH-0260, Kap. 4.22 (neu 4.23) | - |
| #29  | Verarbeitungsreihenfolge präzisieren | DAK 3.1 Kap. 3.10 | - |
| #28  | Kettenlehrverträge | - | eCH-0260 Kap. 2.14 (TV) |
| #27  | Thema 1: Repetitionen lösen neues Teilverhältnis aus | - | - |
| #27  | Thema 2: Streichung isMainResponsible | - | - |
| #27  | Thema 3: Neuer Meldungstyp für vBB (verantw. Berufsbildner) | - | - |
|~~#26~~| ~~VET trainer obligatorisch, aber unbekannt~~ | - | - |~~
| #25  | Txx Gründe für Mutationen können nicht übermittelt werden | XSD, eCH-0260 Kap. 2.16 (neu), 4.18 (neu), 3.11 | - |
| #24  | Neuer Mutationsgrund T05 | SOLL Kap. 3.5.2 | XSD, eCH-0260 Kap. 2.16 (neu) |
| #23  | BSX Code für schoolIdType | DAK 3.8 | - |
| #22  | Schuldaten nicht bekannt bei Versand an VODEX | DAK Kap. 4.4.2.3 | - |
| ~~#21~~  | ~~regex für BUR-number falsch~~ | - | - |
| #19  | legalUnit fehlt in educationContractType | XSD, eCH-0260 Kap. 4.14 | - |
| #18  | Korrespondenzsprache fehlt für VETtrainer | XSD, eCH-0260 Kap. 4.45 (vorher 4.44) | - |
| #18  | Korrespondenzsprache fehlt für Lernende? | - | @AG-DA |
| #17  | Telefonnummer fehlt für "representatives" | XSD, eCH-0260 Kap. 4.37 (vorher 4.36) | @AG-DA |
| #16  | Geburtsdatum nicht Pflicht für VETtrainers | - | XSD, eCH-0260 Kap. 4.45 (vorher 4.44) @AG-DA |
| #15  | "centrallyManaged" nur für LSR relevant | - | XSD, eCH-0260 Kap. 4.28 (vorher 4.27) und 3.2 @AG-DA |
| #14  | QPgradesResponseType - Werteliste fehlt | - | separates Dokument publizieren @AG-DA |
| #13  | Genauere Anweisungen Gesamtbestandsmeldungen | @Marc: Braucht es weitere Vorgaben? | @AG-DA |
| #12  | action-code GR5 nicht korrekt | DAK Kap. 5.6  | - |
| #11  | Beschreibung onlineApplicationsType falsch | eCH-0260 Kap. 4.30 (vorher 4.29) | - |
| #10  | Schema mit Abhängigkeiten nicht vollständig | eCH-0260 Anhang G (Abb. 2) | - |
| #9  | In QPgradesType übermittelte Werte | @Marc: Anpassung eCH/DAK?  | - |
| #8  | Redundanz in VETtrainerType  | @Marc: Entscheid ausstehend? | @AG-DA |
| #7  | @Marc: WEITERE? |  | - |



