---
title: IptcApplicationRecordDataSet
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Definieert IPTC Application Record dataSetnummers.
type: docs
weight: 2890
url: /nl/net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

Definieert IPTC Application Record dataSet-nummers.

```csharp
public enum IptcApplicationRecordDataSet
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| RecordVersion | `0` | Vertegenwoordigt de recordversie. Binair. Altijd 2 in JPEG's. |
| ObjectTypeReference | `3` | Referentie objecttype. Gebruikt patroon: "/\d{2}:[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | De objectattribuutreferentie. |
| ObjectName | `5` | Gebruikt als verkorte referentie voor het object. |
| EditStatus | `7` | Status van de objectgegevens, volgens de praktijk van de provider. |
| EditorialUpdate | `8` | Geeft het type update aan dat dit object levert aan een eerder object. |
| Urgency | `10` | Specificeert de redactionele urgentie van inhoud en niet noodzakelijkerwijs de prioriteit van de envelopbehandeling (zie 1:60, Envelopprioriteit). |
| SubjectReference | `12` | De onderwerpreferentie. |
| Category | `15` | Identificeert het onderwerp van de objectdata volgens de mening van de aanbieder. |
| SupplementalCategory | `20` | Aanvullende categorieën verfijnen het onderwerp van een objectgegevens verder. Elke DataSet mag slechts één aanvullende categorie bevatten. Een aanvullende categorie kan elk van de erkende categorieën bevatten zoals gebruikt in 2:15. |
| FixtureIdentifier | `22` | De armatuur-ID. |
| Keywords | `25` | Wordt gebruikt om specifieke woorden voor het ophalen van informatie aan te geven. Elk trefwoord gebruikt een enkele Trefwoorden DataSet. Meerdere trefwoorden gebruiken meerdere trefwoorden DataSets. |
| ContentLocationCode | `26` | Geeft de code aan van een land/geografische locatie waarnaar wordt verwezen door de inhoud van het object. |
| ContentLocationName | `27` | Biedt een volledige, publiceerbare naam van een land/geografische locatie waarnaar wordt verwezen door de inhoud van het object, volgens richtlijnen van de provider. |
| ReleaseDate | `30` | Geeft in de vorm CCYYMMDD de vroegste datum aan waarop de provider het object wil gebruiken. Volgt de ISO 8601-norm. |
| ReleaseTime | `35` | Geeft in de vorm HHMMSS±UUMM aan wat het vroegste tijdstip is waarop de provider het object wil gebruiken. Volgt de ISO 8601-norm. |
| ExpirationDate | `37` | Geeft in de vorm CCYYMMDD de laatste datum aan waarop de provider of eigenaar de objectgegevens wil gebruiken. Volgt de ISO 8601-norm. |
| SpecialInstructions | `40` | Overige redactionele instructies met betrekking tot het gebruik van de objectdata, zoals embargo's en waarschuwingen. |
| ActionAdvised | `42` | Geeft het type actie aan dat dit object biedt aan een vorig object. |
| ReferenceService | `45` | Identificeert de Service Identifier van een eerdere envelop waarnaar het huidige object verwijst. |
| ReferenceDate | `47` | Identificeert de datum van een eerdere envelop waarnaar het huidige object verwijst. |
| ReferenceNumber | `50` | Identificeert het envelopnummer van een eerdere envelop waarnaar het huidige object verwijst. |
| DateCreated | `55` | Vertegenwoordigd in de vorm CCYYMMDD om de datum aan te geven waarop de intellectuele inhoud van de objectgegevens is gemaakt in plaats van de datum waarop de fysieke representatie is gemaakt. |
| TimeCreated | `60` | Vertegenwoordigd in de vorm HHMMSS±HHMM om de tijd aan te geven waarop de intellectuele inhoud van de objectgegevens huidig bronmateriaal werd gecreëerd in plaats van de creatie van de fysieke representatie. |
| DigitalCreationDate | `62` | Vertegenwoordigd in de vorm CCYYMMDD om de datum aan te geven waarop de digitale weergave van de objectgegevens is gemaakt. |
| DigitalCreationTime | `63` | Weergegeven in de vorm HHMMSS±HHMM om het tijdstip aan te geven waarop de digitale weergave van de objectgegevens is gemaakt. |
| OriginatingProgram | `65` | Identificeert het type programma dat is gebruikt om de objectgegevens te genereren. |
| ProgramVersion | `70` | Gebruikt om de versie van het programma genoemd in 2:65 te identificeren. DataSet 2:70 is ongeldig als 2:65 niet aanwezig is. |
| ObjectCycle | `75` | Bestaande uit een alfabetisch teken. Waar: 'a' = ochtend, 'p' = avond, 'b' = beide. |
| Byline | `80` | Bevat de naam van de maker van de objectgegevens, bijvoorbeeld schrijver, fotograaf of graficus. |
| BylineTitle | `85` | Een by-line titel is de titel van de maker of makers van een objectgegevens. |
| City | `90` | Identificeert de plaats van herkomst van de objectgegevens volgens de richtlijnen opgesteld door de provider. |
| SubLocation | `92` | Identificeert de locatie binnen een stad waar de objectgegevens vandaan komen, volgens richtlijnen opgesteld door de provider. |
| ProvinceState | `95` | Identificeert provincie/staat van herkomst volgens richtlijnen opgesteld door de provider. |
| PrimaryLocationCode | `100` | Geeft de code aan van het land/de primaire locatie waar het intellectuele eigendom van de objectgegevens is gecreëerd, bijv. een foto is gemaakt, een gebeurtenis heeft plaatsgevonden. |
| PrimaryLocationName | `101` | Geeft de volledige, publiceerbare naam van het land/de primaire locatie waar het intellectuele eigendom van de objectdata is gecreëerd, volgens de richtlijnen van de provider. |
| OriginalTransmissionReference | `103` | Een code die de locatie van de oorspronkelijke verzending weergeeft volgens de praktijken van de provider. |
| Headline | `105` | Een publiceerbaar item met een samenvatting van de inhoud van de objectgegevens. |
| Credit | `110` | Identificeert de aanbieder van de objectgegevens, niet noodzakelijkerwijs de eigenaar/maker. |
| Source | `115` | De naam van een persoon of partij die een rol heeft in de content supply chain. Dit kan een bureau zijn, een lid van een bureau, een individu of een combinatie. |
| CopyrightNotice | `116` | Bevat de nodige copyright-kennisgeving. |
| Contact | `118` | Identificeert de persoon of organisatie die verdere achtergrondinformatie over de objectgegevens kan geven. |
| CaptionAbstract | `120` | Een tekstuele beschrijving van de objectgegevens, met name gebruikt wanneer het object geen tekst is. |
| WriterEditor | `122` | Identificatie van de naam van de persoon die betrokken was bij het schrijven, redigeren of corrigeren van de objectdata of caption/abstract. |
| RasterizedCaption | `125` | Beeldbreedte 460 pixels en beeldhoogte 128 pixels. Scanrichting van onder naar boven, van links naar rechts. |
| ImageType | `130` | De numerieke tekens 1 tot 4 geven het aantal componenten in een afbeelding aan, in enkele of meerdere enveloppen. |
| ImageOrientation | `131` | Geeft de lay-out van het afbeeldingsgebied aan. |
| LanguageIdentifier | `135` | Beschrijft de belangrijkste nationale taal van het object, volgens de 2-lettercodes van ISO 639:1988. |
| AudioType | `150` | Het audiotype. |
| AudioSamplingRate | `151` | Bemonsteringsfrequentie numerieke tekens die de bemonsteringsfrequentie in hertz (Hz) vertegenwoordigen. |
| AudioSamplingResolution | `152` | Het aantal bits in elk audiofragment. |
| AudioDuration | `153` | Duur Geeft in de vorm HHMMSS de speelduur van een audio-objectgegevens aan wanneer deze wordt afgespeeld met de snelheid waarmee ze zijn opgenomen. |
| AudioOutcue | `154` | Identificeert de inhoud van het einde van een audio-objectdata, volgens richtlijnen opgesteld door de provider. |
| ObjDataPreviewFileFormat | `200` | Een binair getal dat de bestandsindeling van de ObjectData Preview vertegenwoordigt. |
| ObjDataPreviewFileFormatVer | `201` | Een binair getal dat de specifieke versie vertegenwoordigt van de ObjectData Preview File Format gespecificeerd in 2:200. |
| ObjDataPreviewData | `202` | Het voorbeeld van objectgegevens. |

### Zie ook

* naamruimte [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
