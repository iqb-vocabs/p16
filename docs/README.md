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
| Textschwierigkeit | [Vokabular](https://w3id.org/iqb/v26/ea/) | url: 'https://w3id.org/iqb/v26/ea/', Einmalauswahl | k1 |
| Als SPF-Text geeignet | Ja/Nein |Text für WAHR: ja, Text für FALSCH: nein | a1 |
| Textsorte | [Vokabular](https://w3id.org/iqb/v25/te/) | url: 'https://w3id.org/iqb/v25/te/', Einmalauswahl, Nummerierung unterdrückt | k2 |
| Andere Textsorte | Text |Einzeilig, Sprache(n): de | iqb_other_text_type |
| Notizfeld | Text |Mehrzeilig, Sprache(n): de | iqb_notiz |
| Stimuluszeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
| Aufgabenzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_unit |
| Instruktionszeit | Text |Einzeilig, Sprache(n): de | iqb_time_instructions |
| Anzahl Vorspielen | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_time_play |

### Quellenangabe

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Art der quelle | Text |Mehrzeilig, Sprache(n): de | iqb_art_quelle |
| Vollständige Quellenangabe (Text) | Text |Mehrzeilig, Sprache(n): de | iqb_copyright |

### Hörsequenz

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Anzahl der Sprecher*innen | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_speakers |
| Sprechtempo | [Vokabular](https://w3id.org/iqb/v25/sp/) | url: 'https://w3id.org/iqb/v25/sp/', Einmalauswahl, Nummerierung unterdrückt | k4 |
| Varianten | [Vokabular](https://w3id.org/iqb/v28/dv/) | url: 'https://w3id.org/iqb/v28/dv/', Einmalauswahl, Nummerierung unterdrückt | k5 |
| Nebengeräusche | [Vokabular](https://w3id.org/iqb/v25/ne/) | url: 'https://w3id.org/iqb/v25/ne/', Einmalauswahl, Nummerierung unterdrückt | k6 |
| Hörsequenz Transkript | Text |Mehrzeilig, Sprache(n): de | iqb_transcript |

## Profil "IQB Deutsch Sek I - Item"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p16/master/item.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Lese-/Hörstil | [Vokabular](https://w3id.org/iqb/v26/lh/) | url: 'https://w3id.org/iqb/v26/lh/', Einmalauswahl, Nummerierung unterdrückt | s1 |
| Itemformat | [Vokabular](https://w3id.org/iqb/v27/dp/) | url: 'https://w3id.org/iqb/v27/dp/', Einmalauswahl, Nummerierung unterdrückt | s2 |
| Anforderungsbereich | [Vokabular](https://w3id.org/iqb/v12/a1/) | url: 'https://w3id.org/iqb/v12/a1/', Einmalauswahl, Nummerierung unterdrückt | s3 |
| Bildungsstandard primär | [Vokabular](https://w3id.org/iqb/v34/sm/) | url: 'https://w3id.org/iqb/v34/sm/', Einmalauswahl | s5 |
| Bildungsstandards sekundär | [Vokabular](https://w3id.org/iqb/v34/sm/) | url: 'https://w3id.org/iqb/v34/sm/', Mehrfachauswahl | s6 |
| Itemzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_item |

