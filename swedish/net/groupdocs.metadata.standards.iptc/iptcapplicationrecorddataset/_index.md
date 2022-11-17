---
title: IptcApplicationRecordDataSet
second_title: GroupDocs.Metadata for .NET API-referens
description: Definierar IPTC Application Recorddatauppsättningsnummer.
type: docs
weight: 2890
url: /sv/net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

Definierar IPTC Application Record-datauppsättningsnummer.

```csharp
public enum IptcApplicationRecordDataSet
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| RecordVersion | `0` | Representerar rekordversionen. Binär. Alltid 2 i JPEG. |
| ObjectTypeReference | `3` | Objekttypreferens. Användt mönster: "/\d{2}:[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | Objektattributets referens. |
| ObjectName | `5` | Används som en stenografireferens för objektet. |
| EditStatus | `7` | Status för objektdata, enligt leverantörens praxis. |
| EditorialUpdate | `8` | Indikerar vilken typ av uppdatering som detta objekt tillhandahåller till ett tidigare objekt. |
| Urgency | `10` | Anger innehållets redaktionella brådska och inte nödvändigtvis kuverthanteringsprioriteten (se 1:60, Kuvertprioritet). |
| SubjectReference | `12` | Ämnesreferensen. |
| Category | `15` | Identifierar föremålet för objektdata enligt leverantörens åsikt. |
| SupplementalCategory | `20` | Kompletterande kategorier förfinar ämnet för en objektdata ytterligare. Endast en enda tilläggskategori får finnas i varje datamängd. En tilläggskategori kan inkludera vilken som helst av de erkända kategorierna som används i 2:15. |
| FixtureIdentifier | `22` | Fixturens identifierare. |
| Keywords | `25` | Används för att indikera specifika informationshämtningsord. Varje nyckelord använder en enda nyckelordsdatauppsättning. Flera sökord använder flera sökordsdataset. |
| ContentLocationCode | `26` | Indikerar koden för ett land/geografisk plats som refereras av objektets innehåll. |
| ContentLocationName | `27` | Ger ett fullständigt, publicerbart namn på ett land/geografisk plats som refereras av objektets innehåll, enligt leverantörens riktlinjer. |
| ReleaseDate | `30` | Anger i formuläret CCYYMMDD det tidigaste datum då leverantören avser att objektet ska användas. Följer standarden ISO 8601. |
| ReleaseTime | `35` | Anger i formen HHMMSS±HHMM den tidigaste tidpunkten som leverantören avser att objektet ska användas. Följer standarden ISO 8601. |
| ExpirationDate | `37` | Anger i formuläret CCYYMMDD det senaste datum då leverantören eller ägaren avser att objektdatan ska användas. Följer standarden ISO 8601. |
| SpecialInstructions | `40` | Andra redaktionella instruktioner som rör användningen av objektdata, såsom embargon och varningar. |
| ActionAdvised | `42` | Indikerar typen av åtgärd som detta objekt tillhandahåller ett tidigare objekt. |
| ReferenceService | `45` | Identifierar tjänsteidentifieraren för ett tidigare kuvert som det aktuella objektet refererar till. |
| ReferenceDate | `47` | Identifierar datumet för ett tidigare kuvert som det aktuella objektet refererar till. |
| ReferenceNumber | `50` | Identifierar kuvertnumret för ett tidigare kuvert som det aktuella objektet refererar till. |
| DateCreated | `55` | Representeras i formen CCYYMMDD för att ange datumet då det intellektuella innehållet i objektdatan skapades snarare än datumet då den fysiska representationen skapades. |
| TimeCreated | `60` | Representeras i formen HHMMSS±HHMM för att ange den tidpunkt då det intellektuella innehållet i objektdatan aktuellt källmaterial skapades snarare än skapandet av den fysiska representationen. |
| DigitalCreationDate | `62` | Representeras i formen CCYYMMDD för att ange datumet då den digitala representationen av objektdata skapades. |
| DigitalCreationTime | `63` | Representeras i formen HHMMSS±HHMM för att ange tidpunkten då den digitala representationen av objektdata skapades. |
| OriginatingProgram | `65` | Identifierar typen av program som används för att skapa objektdata. |
| ProgramVersion | `70` | Används för att identifiera versionen av programmet som nämns i 2:65. Dataset 2:70 är ogiltigt om 2:65 inte finns. |
| ObjectCycle | `75` | Består av ett alfabetiskt tecken. Där: 'a' = morgon, 'p' = kväll, 'b' = båda. |
| Byline | `80` | Innehåller namnet på skaparen av objektdata, t.ex. författare, fotograf eller grafiker. |
| BylineTitle | `85` | En by-line titel är titeln på skaparen eller skaparna av en objektdata. |
| City | `90` | Identifierar orten för objektdatans ursprung enligt riktlinjer som fastställts av leverantören. |
| SubLocation | `92` | Identifierar platsen i en stad från vilken objektdatan kommer från, enligt riktlinjer fastställda av leverantören. |
| ProvinceState | `95` | Identifierar provins/ursprungsstat enligt riktlinjer fastställda av leverantören. |
| PrimaryLocationCode | `100` | Indikerar koden för landet/den primära platsen där den immateriella äganderätten till objektdata skapades, t.ex. ett foto togs, en händelse inträffade. |
| PrimaryLocationName | `101` | Tillhandahåller fullständigt, publicerbart namn på landet/den primära platsen där den immateriella äganderätten till objektdata skapades, enligt leverantörens riktlinjer. |
| OriginalTransmissionReference | `103` | En kod som representerar platsen för den ursprungliga överföringen enligt leverantörens praxis. |
| Headline | `105` | En publicerbar post som ger en sammanfattning av innehållet i objektdata. |
| Credit | `110` | Identifierar leverantören av objektdata, inte nödvändigtvis ägaren/skaparen. |
| Source | `115` | Namnet på en person eller part som har en roll i innehållsförsörjningskedjan. Detta kan vara en byrå, en medlem av en byrå, en individ eller en kombination. |
| CopyrightNotice | `116` | Innehåller alla nödvändiga upphovsrättsmeddelanden. |
| Contact | `118` | Identifierar den person eller organisation som kan ge ytterligare bakgrundsinformation om objektdata. |
| CaptionAbstract | `120` | En textbeskrivning av objektdata, speciellt använd där objektet inte är text. |
| WriterEditor | `122` | Identifiering av namnet på den person som är involverad i att skriva, redigera eller korrigera objektdata eller bildtext/abstract. |
| RasterizedCaption | `125` | Bildbredd 460 pixlar och bildhöjd 128 pixlar. Skanningsriktning nedifrån och upp, från vänster till höger. |
| ImageType | `130` | De numeriska tecknen 1 till 4 indikerar antalet komponenter i en bild, i enstaka eller flera kuvert. |
| ImageOrientation | `131` | Indikerar layouten för bildområdet. |
| LanguageIdentifier | `135` | Beskriver det huvudsakliga nationella språket för objektet, enligt 2-bokstavskoderna i ISO 639:1988. |
| AudioType | `150` | Ljudtypen. |
| AudioSamplingRate | `151` | Samplingsfrekvens numeriska tecken, representerar samplingsfrekvensen i hertz (Hz). |
| AudioSamplingResolution | `152` | Antalet bitar i varje ljudsampel. |
| AudioDuration | `153` | Duration Anger i formen HHMMSS körtiden för ett ljudobjektsdata när det spelas upp med den hastighet som det spelades in. |
| AudioOutcue | `154` | Identifierar innehållet i slutet av ett ljudobjektdata, enligt riktlinjer som fastställts av leverantören. |
| ObjDataPreviewFileFormat | `200` | Ett binärt tal som representerar filformatet för ObjectData Preview. |
| ObjDataPreviewFileFormatVer | `201` | Ett binärt tal som representerar den specifika versionen av ObjectData Preview File Format som anges i 2:200. |
| ObjDataPreviewData | `202` | Förhandsgranskningen av objektdata. |

### Se även

* namnutrymme [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
