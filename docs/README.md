# Metadatenprofile für Testaufgaben: Deutsch Sek I

ID of profile-store: `des1`

Publisher: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

Maintainer: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

2 Profile definiert:

## Profil "IQB Deutsch Sek I - Aufgabe"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p16/master/unit.json`

### Stimulus

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Entwickler*in | Text |Einzeilig, Sprache(n): de | iqb_author |
| Für SPF geeignet | Ja/Nein |Text für WAHR: ja, Text für FALSCH: nein | a1 |
| Kopfhörereinsatz | [Vokabular](https://w3id.org/iqb/v24/kh/) | url: 'https://w3id.org/iqb/v24/kh/', Einmalauswahl, Nummerierung unterdrückt | iqb_phones |
| Schulform | [Vokabular](https://w3id.org/kim/schularten/) | url: 'https://w3id.org/kim/schularten/', Einmalauswahl, Nummerierung unterdrückt | kim_type_school |
| Kompetenzbereich | [Vokabular](https://w3id.org/iqb/v34/sm/) | url: 'https://w3id.org/iqb/v34/sm/', Einmalauswahl, Zeige nur erste Ebene | w8 |
| Texttyp | [Vokabular](https://w3id.org/iqb/v28/ts/) | url: 'https://w3id.org/iqb/v28/ts/', Einmalauswahl, Nummerierung unterdrückt | k1 |
| Textsorte | [Vokabular](https://w3id.org/iqb/v28/ss/) | url: 'https://w3id.org/iqb/v28/ss/', Einmalauswahl, Nummerierung unterdrückt | k2 |
| Notizfeld | Text |Mehrzeilig, Sprache(n): de | iqb_note |
| Angaben zum Urtext und zu Inspirationsquellen | Text |Mehrzeilig, Sprache(n): de | iqb_additional_info |
| Stimuluszeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
| Aufgabenzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_unit |
| Instruktionszeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_time_instructions |
| Anzahl Vorspielen | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_time_play |
| Unverträgliche Aufgaben | Text |Einzeilig, Sprache(n): de | iqb_compatibility |

### Quellenangabe

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Art der Quelle(n) | [Vokabular](https://w3id.org/iqb/v28/aq/) | url: 'https://w3id.org/iqb/v28/aq/', Einmalauswahl | k3 |
| Vollständige Quellenangabe (Text) | Text |Mehrzeilig, Sprache(n): de | iqb_copyright |

### Hörsequenz

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Anzahl der Sprecher*innen | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_speakers |
| Sprechtempo | [Vokabular](https://w3id.org/iqb/v25/sp/) | url: 'https://w3id.org/iqb/v25/sp/', Einmalauswahl, Nummerierung unterdrückt | k4 |
| Varianten | [Vokabular](https://w3id.org/iqb/v28/dv/) | url: 'https://w3id.org/iqb/v28/dv/', Mehrfachauswahl, Nummerierung unterdrückt | k5 |
| Nebengeräusche | [Vokabular](https://w3id.org/iqb/v25/ne/) | url: 'https://w3id.org/iqb/v25/ne/', Einmalauswahl, Nummerierung unterdrückt | k6 |
| Transkript | Text |Mehrzeilig, Sprache(n): de | iqb_transcript |

## Profil "IQB Deutsch Sek I - Item"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p16/master/item.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Lese-/Hörstil | [Vokabular](https://w3id.org/iqb/v26/lh/) | url: 'https://w3id.org/iqb/v26/lh/', Einmalauswahl, Nummerierung unterdrückt | s1 |
| Itemformat | [Vokabular](https://w3id.org/iqb/v27/ds/) | url: 'https://w3id.org/iqb/v27/ds/', Einmalauswahl, Nummerierung unterdrückt | s2 |
| Anforderungsbereich | [Vokabular](https://w3id.org/iqb/v34/a1/) | url: 'https://w3id.org/iqb/v34/a1/', Einmalauswahl, Nummerierung unterdrückt | s3 |
| Bildungsstandard ESA - primär | [Vokabular](https://w3id.org/iqb/v34/se/) | url: 'https://w3id.org/iqb/v34/se/', Einmalauswahl | s7 |
| Bildungsstandards ESA - sekundär | [Vokabular](https://w3id.org/iqb/v34/se/) | url: 'https://w3id.org/iqb/v34/se/', Mehrfachauswahl | s8 |
| Bildungsstandard MSA - primär | [Vokabular](https://w3id.org/iqb/v34/sm/) | url: 'https://w3id.org/iqb/v34/sm/', Einmalauswahl | s5 |
| Bildungsstandards MSA - sekundär | [Vokabular](https://w3id.org/iqb/v34/sm/) | url: 'https://w3id.org/iqb/v34/sm/', Mehrfachauswahl | s6 |
| Itemzeit (IQB intern) | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_item |
| Geschätzte Schwierigkeit | [Vokabular](https://w3id.org/iqb/v26/ea/) | url: 'https://w3id.org/iqb/v26/ea/', Einmalauswahl | e4 |
| Technische Besonderheiten der Antwortoptionen | [Vokabular](https://w3id.org/iqb/v27/ti/) | url: 'https://w3id.org/iqb/v27/ti/', Mehrfachauswahl | iqb_itemtech |

