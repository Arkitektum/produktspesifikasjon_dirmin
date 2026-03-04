---
title: "Rapporter etter undersøkelser på statens mineraler WMS"
updated: "2026-01-23"
organization: "Direktoratet for mineralforvaltning"
logo: "https://register.geonorge.no/data/organizations/974760282_DMF_liten.png"
---

# Produktspesifikasjon: Rapporter etter undersøkelser på statens mineraler WMS

## Generelt om spesifikasjonen


### Unik identifisering

3f59e82c-217b-4092-a1dc-6327a9c3bfbf

#### Fullstendig navn

Rapporter etter undersøkelser på statens mineraler WMS

#### Versjon

2018-04-27

### Ansvarlig organisasjon

Direktoratet for mineralforvaltning

### Hovedtema

Statens mineraler, Bergrettigheter, Mineralogi, Petrologi, Geofysikk, Geokjemi, Prospektering, Leting, Undersøkelser, Mineral, Norge fastland, Geologi, Mineralressurser, DMF, dirmin

### Sammendrag

Rapporter etter undersøkelser på statens mineraler er rapportering av utførte undersøkelsesarbeider innenfor et område med undersøkelsesrettigheter. Dette kan være geologiske og geofysiske arbeider som er utført av rettighetshavere.

Tjenesten viser undersøkelsesrapporter som Direktoratet for mineralforvaltning (DMF) har mottatt, basert på rettigheter gitt etter mineralloven, og som er digitalt stedfestet (punkt) og godkjent.

Vennligst bruk "KONTAKT OSS"-skjemaet på <https://minit.dirmin.no/kart> hvis du/dere ønsker å gi oss tilbakemeldinger knyttet til registreringene.

### Formål

The mineral rights reports give an overview over the exploration work performed in areas with mineral rights in order to increase the knowledge of the mineral resources present.

## Spesifikasjonsomfang

- **Omfang**:

  - **Identifikasjon**: hele datasettet
  - **Nivå**: service

## Innhold og struktur

**Beskrivelse**: Rapportene kan brukes til å få en oversikt over hva som er utført av arbeider i områder med bergrettigheter for å øke kunnskapen om de mineralske ressurser til stede.

### Datamodell





<a href="undersokelsesrapporter_feature_catalogue.png" title="Klikk for stor visning"><img src="undersokelsesrapporter_feature_catalogue.png" alt="Undersokelsesrapporter feature catalogue" style="max-width: 100%; height: auto;" /></a>

#### Undersoekelsesrapport

Geometri:<br />Type: GM_MultiPoint<br />Koordinatreferansesystem (crs):<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84"><http://www.opengis.net/def/crs/OGC/1.3/CRS84></a><br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833"><http://www.opengis.net/def/crs/EPSG/0/25833></a><br />• <a href="http://www.opengis.net/def/crs/EPSG/0/32633"><http://www.opengis.net/def/crs/EPSG/0/32633></a><br />• <a href="http://www.opengis.net/def/crs/EPSG/0/4326"><http://www.opengis.net/def/crs/EPSG/0/4326></a><br />• <a href="http://www.opengis.net/def/crs/EPSG/0/3857"><http://www.opengis.net/def/crs/EPSG/0/3857></a>

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geometry</strong></td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_MultiPoint</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>Rapportnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>Rapporttittel</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>boolean</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>Kommunenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>Kommunenavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>Fylkesnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>Fylkesnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
    </tr>
  </tbody>
</table>



## Kvalitet

**Nivå**: service





## Datavedlikehold

**Vedlikeholdsfrekvens**: Kontinuerlig

## Leveranse

- **Leveranse**:

  - **Leveransemedium**:
    - **Medienavn**: OGC:WMS
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://kart.dirmin.no/dirmin/services/UndersoekelseRapporter/MapServer/WMSServer?request=GetCapabilities&service=WMS>
      - **Tjenesteegenskap**:
        - **type**: OGC:WMS
        - **Verdi**: OGC:WMS

- **Leveranse**:

  - **Leveransemedium**:
    - **Medienavn**: WMS-tjeneste
    - **Leveransetjeneste**:
      - **Tjenesteendepunkt**: <https://kart.dirmin.no/dirmin/services/UndersoekelseRapporter/MapServer/WMSServer?request=GetCapabilities&service=WMS>
      - **Tjenesteegenskap**:
        - **type**: WMS-tjeneste
        - **Verdi**: OGC:WMS

## Metadata

**Metadatastandard**: ISO19115

**Metadatastandardversjon**: 2003

**Metadatadato**: 2023-01-12

**språk**: nor

**Kontakt**:

- **Organisasjon**: Direktoratet for mineralforvaltning
- **Kontaktperson**: IT-utvikling
- **Logo**: <https://register.geonorge.no/data/organizations/974760282_DMF_liten.png>
- **Epost**: post@dirmin.no
- **rolle**: pointOfContact

**Metadataidentifikator**:

- **Utsteder**: Geonorge
- **kode**: 3f59e82c-217b-4092-a1dc-6327a9c3bfbf
- **koderom**: <https://kartkatalog.geonorge.no/metadata/>
- **Metadatalenke**: <https://kartkatalog.geonorge.no/metadata/3f59e82c-217b-4092-a1dc-6327a9c3bfbf>

**Lenker**:

- **lenke**: <https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=3f59e82c-217b-4092-a1dc-6327a9c3bfbf>
  **relasjon**: describedby
  **type**: application/xml
  **tittel**: Metadata (ISO 19139)

- **lenke**: <https://kart.dirmin.no/dirmin/services/UndersoekelseRapporter/MapServer/WMSServer?request=GetCapabilities&service=WMS>
  **relasjon**: enclosure
  **type**: text/html
  **tittel**: Nedlasting
