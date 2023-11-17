<!-- 10-Header -->    
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)    
Entität: Projekt    
================<!-- /10-Header -->    
<!-- 15-License -->    
[Offene Lizenz](https://github.com/smart-data-models//dataModel.SDG/blob/master/Project/LICENSE.md)    
[Dokument automatisch generiert](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)    
<!-- /15-License -->    
<!-- 20-Description -->    
Globale Beschreibung: **Satz von Aktivitäten, die, wenn sie ausgeführt werden, die Erfüllung eines strategischen Ziels unterstützen (Bereitstellung von Schlüsseldienstleistungen, Managemententwicklung, enger Kontakt mit dem Gebiet, Unternehmensförderung, gezielte Investitionen, soziale/kulturelle/sportliche Förderung, usw.). Dieses Ziel selbst setzt sich aus einem oder mehreren Projekten zusammen und bezieht sich auf eine der strategischen Achsen (Arbeitsmodell, wirtschaftliche Entwicklung, soziale Entwicklung, ökologische Entwicklung), die dem Strategieplan ein hohes Maß an Gestalt verleihen**    
Version: 0.0.1    
<!-- /20-Description -->    
<!-- 30-PropertiesList -->    
## Liste der Eigenschaften    
<sup><sub>[*] Wenn es für ein Attribut keinen Typ gibt, kann es mehrere Typen oder verschiedene Formate/Muster haben</sub></sup>.    
- `address[object]`: Die Postanschrift  . Model: [https://schema.org/address](https://schema.org/address)	- `addressCountry[string]`: Das Land. Zum Beispiel, Spanien  . Model: [https://schema.org/addressCountry](https://schema.org/addressCountry)    
	- `addressLocality[string]`: Die Ortschaft, in der sich die Adresse befindet, und die in der Region liegt  . Model: [https://schema.org/addressLocality](https://schema.org/addressLocality)    
	- `addressRegion[string]`: Die Region, in der sich der Ort befindet, und die auf dem Land liegt  . Model: [https://schema.org/addressRegion](https://schema.org/addressRegion)    
	- `district[string]`: Ein Bezirk ist eine Art von Verwaltungseinheit, die in einigen Ländern von der lokalen Regierung verwaltet wird.      
	- `postOfficeBoxNumber[string]`: Die Postfachnummer für Postfachadressen. Zum Beispiel, 03578  . Model: [https://schema.org/postOfficeBoxNumber](https://schema.org/postOfficeBoxNumber)    
	- `postalCode[string]`: Die Postleitzahl. Zum Beispiel, 24004  . Model: [https://schema.org/https://schema.org/postalCode](https://schema.org/https://schema.org/postalCode)    
	- `streetAddress[string]`: Die Straßenanschrift  . Model: [https://schema.org/streetAddress](https://schema.org/streetAddress)    
- `alternateName[string]`: Ein alternativer Name für diesen Artikel  - `areaServed[string]`: Das geografische Gebiet, in dem eine Dienstleistung oder ein angebotener Artikel erbracht wird  . Model: [https://schema.org/Text](https://schema.org/Text)- `axis[string]`: Strategische Achse, zu der das Projekt gehört  - `challenges[string]`: Herausforderungen, die das Projekt zu bewältigen hat  - `dataProvider[string]`: Eine Folge von Zeichen zur Identifizierung des Anbieters der harmonisierten Dateneinheit  - `dateCreated[date-time]`: Zeitstempel der Entitätserstellung. Dieser wird normalerweise von der Speicherplattform zugewiesen  - `dateModified[date-time]`: Zeitstempel der letzten Änderung der Entität. Dieser wird in der Regel von der Speicherplattform vergeben  - `delegations[array]`: Delegationen oder interne Abteilungen, zu denen das Projekt gehört  - `delegationsInvolved[array]`: An dem Projekt beteiligte Delegationen oder interne Abteilungen  - `description[string]`: Eine Beschreibung dieses Artikels  - `id[*]`: Eindeutiger Bezeichner der Entität  - `interestGroups[array]`: An dem Projekt beteiligte Delegationen oder interne Abteilungen  - `location[*]`: Geojson-Referenz auf das Element. Es kann Punkt, LineString, Polygon, MultiPoint, MultiLineString oder MultiPolygon sein  - `modifications[string]`: Änderungen, die das Projekt in eine mögliche Aktualisierung aufgenommen hat  - `name[string]`: Der Name dieses Artikels  - `observations[string]`: Freier Text über besondere Merkmale des Projekts  - `owner[array]`: Eine Liste mit einer JSON-kodierten Zeichenfolge, die auf die eindeutigen Kennungen der Eigentümer verweist  - `plan[string]`: Unterart des Projekts. Enum:'EDS, PPE'  - `refDevice[array]`: Für die Messung verwendete(s) Gerät(e)  - `sdg[string]`: Ziel der nachhaltigen Entwicklung, zu dem das Projekt gehört  - `seeAlso[*]`: Liste von URLs, die auf zusätzliche Ressourcen zu dem Artikel verweisen  - `source[string]`: Eine Folge von Zeichen, die die ursprüngliche Quelle der Entitätsdaten als URL angibt. Empfohlen wird der voll qualifizierte Domänenname des Quellanbieters oder die URL des Quellobjekts.  - `strategicObjective[string]`: Strategisches Ziel, zu dem das Projekt gehört  - `type[string]`: Sie muss gleich dem Projekt sein  <!-- /30-PropertiesList -->    
<!-- 35-RequiredProperties -->    
Erforderliche Eigenschaften    
- `id`  - `type`  <!-- /35-RequiredProperties -->    
<!-- 40-RequiredProperties -->    
<!-- /40-RequiredProperties -->    
<!-- 50-DataModelHeader -->    
## Datenmodell Beschreibung der Eigenschaften    
Alphabetisch sortiert (für Details anklicken)    
<!-- /50-DataModelHeader -->    
<!-- 60-ModelYaml -->    
<details><summary><strong>full yaml details</strong></summary>      
```yaml    
Project:      
  description: 'Set of activities that, when executed support the compliance of a strategic goal (Provision of Key Services, Management Evolution, Close contact with Territory, Enterprises Boosting, Focused Investment, Social/Cultural/Sports Promotion, etc.). This goal itself is composed of one or more project,s and address one of the strategic axes (Work model, Economic development, Social development, Environmental Development) that give a high level shape to the Strategic Plan'      
  properties:      
    address:      
      description: The mailing address      
      properties:      
        addressCountry:      
          description: 'The country. For example, Spain'      
          type: string      
          x-ngsi:      
            model: https://schema.org/addressCountry      
            type: Property      
        addressLocality:      
          description: 'The locality in which the street address is, and which is in the region'      
          type: string      
          x-ngsi:      
            model: https://schema.org/addressLocality      
            type: Property      
        addressRegion:      
          description: 'The region in which the locality is, and which is in the country'      
          type: string      
          x-ngsi:      
            model: https://schema.org/addressRegion      
            type: Property      
        district:      
          description: 'A district is a type of administrative division that, in some countries, is managed by the local government'      
          type: string      
          x-ngsi:      
            type: Property      
        postOfficeBoxNumber:      
          description: 'The post office box number for PO box addresses. For example, 03578'      
          type: string      
          x-ngsi:      
            model: https://schema.org/postOfficeBoxNumber      
            type: Property      
        postalCode:      
          description: 'The postal code. For example, 24004'      
          type: string      
          x-ngsi:      
            model: https://schema.org/https://schema.org/postalCode      
            type: Property      
        streetAddress:      
          description: The street address      
          type: string      
          x-ngsi:      
            model: https://schema.org/streetAddress      
            type: Property      
        streetNr:      
          description: Number identifying a specific property on a public street      
          type: string      
          x-ngsi:      
            type: Property      
      type: object      
      x-ngsi:      
        model: https://schema.org/address      
        type: Property      
    alternateName:      
      description: An alternative name for this item      
      type: string      
      x-ngsi:      
        type: Property      
    areaServed:      
      description: The geographic area where a service or offered item is provided      
      type: string      
      x-ngsi:      
        model: https://schema.org/Text      
        type: Property      
    axis:      
      description: Strategic axis the project belongs to      
      type: string      
      x-ngsi:      
        type: Property      
    challenges:      
      description: 'Challenges to be faced by the project '      
      type: string      
      x-ngsi:      
        type: Property      
    dataProvider:      
      description: A sequence of characters identifying the provider of the harmonised data entity      
      type: string      
      x-ngsi:      
        type: Property      
    dateCreated:      
      description: Entity creation timestamp. This will usually be allocated by the storage platform      
      format: date-time      
      type: string      
      x-ngsi:      
        type: Property      
    dateModified:      
      description: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform      
      format: date-time      
      type: string      
      x-ngsi:      
        type: Property      
    delegations:      
      description: Delegations or internal departments the project belongs to      
      items:      
        type: string      
      type: array      
      x-ngsi:      
        type: Property      
    delegationsInvolved:      
      description: Delegations or internal departments involved in the project      
      items:      
        type: string      
      type: array      
      x-ngsi:      
        type: Property      
    description:      
      description: A description of this item      
      type: string      
      x-ngsi:      
        type: Property      
    id:      
      anyOf:      
        - description: Identifier format of any NGSI entity      
          maxLength: 256      
          minLength: 1      
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$      
          type: string      
          x-ngsi:      
            type: Property      
        - description: Identifier format of any NGSI entity      
          format: uri      
          type: string      
          x-ngsi:      
            type: Property      
      description: Unique identifier of the entity      
      x-ngsi:      
        type: Property      
    interestGroups:      
      description: Delegations or internal departments involved in the project      
      items:      
        type: string      
      type: array      
      x-ngsi:      
        type: Property      
    location:      
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'      
      oneOf:      
        - description: Geojson reference to the item. Point      
          properties:      
            bbox:      
              items:      
                type: number      
              minItems: 4      
              type: array      
            coordinates:      
              items:      
                type: number      
              minItems: 2      
              type: array      
            type:      
              enum:      
                - Point      
              type: string      
          required:      
            - type      
            - coordinates      
          title: GeoJSON Point      
          type: object      
          x-ngsi:      
            type: GeoProperty      
        - description: Geojson reference to the item. LineString      
          properties:      
            bbox:      
              items:      
                type: number      
              minItems: 4      
              type: array      
            coordinates:      
              items:      
                items:      
                  type: number      
                minItems: 2      
                type: array      
              minItems: 2      
              type: array      
            type:      
              enum:      
                - LineString      
              type: string      
          required:      
            - type      
            - coordinates      
          title: GeoJSON LineString      
          type: object      
          x-ngsi:      
            type: GeoProperty      
        - description: Geojson reference to the item. Polygon      
          properties:      
            bbox:      
              items:      
                type: number      
              minItems: 4      
              type: array      
            coordinates:      
              items:      
                items:      
                  items:      
                    type: number      
                  minItems: 2      
                  type: array      
                minItems: 4      
                type: array      
              type: array      
            type:      
              enum:      
                - Polygon      
              type: string      
          required:      
            - type      
            - coordinates      
          title: GeoJSON Polygon      
          type: object      
          x-ngsi:      
            type: GeoProperty      
        - description: Geojson reference to the item. MultiPoint      
          properties:      
            bbox:      
              items:      
                type: number      
              minItems: 4      
              type: array      
            coordinates:      
              items:      
                items:      
                  type: number      
                minItems: 2      
                type: array      
              type: array      
            type:      
              enum:      
                - MultiPoint      
              type: string      
          required:      
            - type      
            - coordinates      
          title: GeoJSON MultiPoint      
          type: object      
          x-ngsi:      
            type: GeoProperty      
        - description: Geojson reference to the item. MultiLineString      
          properties:      
            bbox:      
              items:      
                type: number      
              minItems: 4      
              type: array      
            coordinates:      
              items:      
                items:      
                  items:      
                    type: number      
                  minItems: 2      
                  type: array      
                minItems: 2      
                type: array      
              type: array      
            type:      
              enum:      
                - MultiLineString      
              type: string      
          required:      
            - type      
            - coordinates      
          title: GeoJSON MultiLineString      
          type: object      
          x-ngsi:      
            type: GeoProperty      
        - description: Geojson reference to the item. MultiLineString      
          properties:      
            bbox:      
              items:      
                type: number      
              minItems: 4      
              type: array      
            coordinates:      
              items:      
                items:      
                  items:      
                    items:      
                      type: number      
                    minItems: 2      
                    type: array      
                  minItems: 4      
                  type: array      
                type: array      
              type: array      
            type:      
              enum:      
                - MultiPolygon      
              type: string      
          required:      
            - type      
            - coordinates      
          title: GeoJSON MultiPolygon      
          type: object      
          x-ngsi:      
            type: GeoProperty      
      x-ngsi:      
        type: GeoProperty      
    modifications:      
      description: 'Changes that the project has incorporated in a possible update '      
      type: string      
      x-ngsi:      
        type: Property      
    name:      
      description: The name of this item      
      type: string      
      x-ngsi:      
        type: Property      
    observations:      
      description: Free text about specific characteristics of the project      
      type: string      
      x-ngsi:      
        type: Property      
    owner:      
      description: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)      
      items:      
        anyOf:      
          - description: Identifier format of any NGSI entity      
            maxLength: 256      
            minLength: 1      
            pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$      
            type: string      
            x-ngsi:      
              type: Property      
          - description: Identifier format of any NGSI entity      
            format: uri      
            type: string      
            x-ngsi:      
              type: Property      
        description: Unique identifier of the entity      
        x-ngsi:      
          type: Property      
      type: array      
      x-ngsi:      
        type: Property      
    plan:      
      description: 'Subtype of project. Enum:''EDS, PPE'''      
      enum:      
        - EDS      
        - PPE      
      type: string      
      x-ngsi:      
        type: Property      
    refDevice:      
      description: Device(s) used to obtain the measurement      
      items:      
        anyOf:      
          - description: Identifier format of any NGSI entity      
            maxLength: 256      
            minLength: 1      
            pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$      
            type: string      
            x-ngsi:      
              type: Property      
          - description: Identifier format of any NGSI entity      
            format: uri      
            type: string      
            x-ngsi:      
              type: Property      
        description: Unique identifier of the entity      
        x-ngsi:      
          type: Property      
      minItems: 1      
      type: array      
      uniqueItems: true      
      x-ngsi:      
        type: Relationship      
    sdg:      
      description: 'Sustainable Development goal the project belongs to '      
      type: string      
      x-ngsi:      
        type: Property      
    seeAlso:      
      description: list of uri pointing to additional resources about the item      
      oneOf:      
        - items:      
            format: uri      
            type: string      
          minItems: 1      
          type: array      
        - format: uri      
          type: string      
      x-ngsi:      
        type: Property      
    source:      
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object'      
      type: string      
      x-ngsi:      
        type: Property      
    strategicObjective:      
      description: 'Strategic objective the project belongs to '      
      type: string      
      x-ngsi:      
        type: Property      
    type:      
      description: It must be equal to Project      
      enum:      
        - Project      
      type: string      
      x-ngsi:      
        type: Property      
  required:      
    - id      
    - type      
  type: object      
  x-derived-from: ""      
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2022 Contributors to Smart Data Models Program'      
  x-license-url: https://github.com/smart-data-models/dataModel.SDG/blob/master/Project/LICENSE.md      
  x-model-schema: https://smart-data-models.github.io/dataModel.SDG/Project/schema.json      
  x-model-tags: SDG      
  x-version: 0.0.1      
```    
</details>      
<!-- /60-ModelYaml -->    
<!-- 70-MiddleNotes -->    
<!-- /70-MiddleNotes -->    
<!-- 80-Examples -->    
## Beispiel-Nutzlasten    
#### Projekt NGSI-v2 Schlüsselwerte Beispiel    
Hier ist ein Beispiel für ein Projekt im JSON-LD-Format als Key-Values. Dies ist mit NGSI-v2 kompatibel, wenn `options=keyValues` verwendet wird und liefert die Kontextdaten einer einzelnen Entität.    
<details><summary><strong>show/hide example</strong></summary>      
```json  
{  
  "id": "0.E.6.AY1",  
  "type": "Project",  
  "plan": "EDS",  
  "delegations": [  
    "TRANSFORMATION DIGITAL Y TURISMO"  
  ],  
  "delegationsInvolved": [  
    "BIENESTAR SOCIAL",  
    "CONCERTACION Y PARTICIPACION TERRITORIAL"  
  ],  
  "dateCreated": "2016-08-08T10:18:16Z",  
  "dateModified": "2016-08-08T10:18:16Z",  
  "name": "O.E.6.AY1 Plan Smart Provincia",  
  "description": "Realizar un estudio que permita conocer las necesidades de nuevos servicios que a futuro deba prestar la DiputaciOn de Badajoz, de modo que le permita anticiparte y adaptarse a las nuevas necesidades de todos sus grupos de interes. Analizar cmo mejorar el cumplimiento de los ODS por parte de la Diputaci6n con nuevas actuaciones y eliminacion de otras obsoletas ejecutadas por rutina y sin evaluar.",  
  "axisN": "B. DESARROLLO ECONOMICO",  
  "interestGroups": [  
    "AYUNTAMIENTOS"  
  ]  
}  
```  
</details>    
#### Projekt NGSI-v2 normalisiert Beispiel    
Hier ist ein Beispiel für ein Projekt im JSON-LD-Format in normalisierter Form. Dies ist kompatibel mit NGSI-v2, wenn keine Optionen verwendet werden, und liefert die Kontextdaten einer einzelnen Entität.    
<details><summary><strong>show/hide example</strong></summary>      
```json  
{  
  "id": "0.E.6.AY1",  
  "type": "Project",  
  "plan": {  
    "type": "Text",  
    "value": "EDS"  
  },  
  "delegations": {  
    "type": "StructuredValue",  
    "value": [  
      "TRANSFORMATION DIGITAL Y TURISMO"  
    ]  
  },  
  "delegationsInvolved": {  
    "type": "StructuredValue",  
    "value": [  
      "BIENESTAR SOCIAL",  
      "CONCERTACION Y PARTICIPACION TERRITORIAL"  
    ]  
  },  
  "dateCreated": {  
    "type": "DateTime",  
    "value": "2016-08-08T10:18:16Z"  
  },  
  "dateModified": {  
    "type": "DateTime",  
    "value": "2016-08-08T10:18:16Z"  
  },  
  "name": {  
    "type": "Text",  
    "value": "O.E.6.AY1 Plan Smart Provincia"  
  },  
  "description": {  
    "type": "Text",  
    "value": "Realizar un estudio que permita conocer las necesidades de nuevos servicios que a futuro deba prestar la DiputaciOn de Badajoz, de modo que le permita anticiparte y adaptarse a las nuevas necesidades de todos sus grupos de interes. Analizar cmo mejorar el cumplimiento de los ODS por parte de la Diputaci6n con nuevas actuaciones y eliminacion de otras obsoletas ejecutadas por rutina y sin evaluar."  
  },  
  "axisN": {  
    "type": "Text",  
    "value": "B. DESARROLLO ECONOMICO"  
  },  
  "interestGroups": {  
    "type": "StructuredValue",  
    "value": [  
      "AYUNTAMIENTOS"  
    ]  
  }  
}  
```  
</details>    
#### Projekt NGSI-LD Schlüsselwerte Beispiel    
Hier ist ein Beispiel für ein Projekt im JSON-LD-Format als Key-Values. Dies ist mit NGSI-LD kompatibel, wenn `options=keyValues` verwendet wird und liefert die Kontextdaten einer einzelnen Entität.    
<details><summary><strong>show/hide example</strong></summary>      
```json  
{  
  "id": "urn:ngsi-ld:0.E.6.AY1",  
  "type": "Project",  
  "plan": "EDS",  
  "delegations": [  
    "TRANSFORMATION DIGITAL Y TURISMO"  
  ],  
  "delegationsInvolved": [  
    "BIENESTAR SOCIAL",  
    "CONCERTACION Y PARTICIPACION TERRITORIAL"  
  ],  
  "dateCreated": "2016-08-08T10:18:16Z",  
  "dateModified": "2016-08-08T10:18:16Z",  
  "name": "O.E.6.AY1 Plan Smart Provincia",  
  "description": "Realizar un estudio que permita conocer las necesidades de nuevos servicios que a futuro deba prestar la DiputaciOn de Badajoz, de modo que le permita anticiparte y adaptarse a las nuevas necesidades de todos sus grupos de interes. Analizar cmo mejorar el cumplimiento de los ODS por parte de la Diputaci6n con nuevas actuaciones y eliminacion de otras obsoletas ejecutadas por rutina y sin evaluar.",  
  "axisN": "B. DESARROLLO ECONOMICO",  
  "interestGroups": [  
    "AYUNTAMIENTOS"  
  ],  
  "@context": [  
    "https://smart-data-models.github.io/dataModel.SDG/context.jsonld"  
  ]  
}  
```  
</details>    
#### Projekt NGSI-LD normalisiert Beispiel    
Hier ist ein Beispiel für ein Projekt im JSON-LD-Format in normalisierter Form. Dies ist kompatibel mit NGSI-LD, wenn keine Optionen verwendet werden, und liefert die Kontextdaten einer einzelnen Entität.    
<details><summary><strong>show/hide example</strong></summary>      
```json  
{  
  "id": "0.E.6.AY1",  
  "type": "Project",  
  "plan": {  
    "type": "Property",  
    "value": "EDS"  
  },  
  "delegations": {  
    "type": "Property",  
    "value": [  
      "TRANSFORMATION DIGITAL Y TURISMO"  
    ]  
  },  
  "delegationsInvolved": {  
    "type": "Property",  
    "value": [  
      "BIENESTAR SOCIAL",  
      "CONCERTACION Y PARTICIPACION TERRITORIAL"  
    ]  
  },  
  "dateCreated": {  
    "type": "Property",  
    "value": {  
      "@type": "Date-Time",  
      "@value": "2016-08-08T10:18:16Z"  
    }  
  },  
  "dateModified": {  
    "type": "Property",  
    "value": {  
      "@type": "Date-Time",  
      "@value": "2016-08-08T10:18:16Z"  
    }  
  },  
  "name": {  
    "type": "Property",  
    "value": "O.E.6.AY1 Plan Smart Provincia"  
  },  
  "description": {  
    "type": "Property",  
    "value": "Realizar un estudio que permita conocer las necesidades de nuevos servicios que a futuro deba prestar la DiputaciOn de Badajoz, de modo que le permita anticiparte y adaptarse a las nuevas necesidades de todos sus grupos de interes. Analizar cmo mejorar el cumplimiento de los ODS por parte de la Diputaci6n con nuevas actuaciones y eliminacion de otras obsoletas ejecutadas por rutina y sin evaluar."  
  },  
  "axisN": {  
    "type": "Property",  
    "value": "B. DESARROLLO ECONOMICO"  
  },  
  "interestGroups": {  
    "type": "Property",  
    "value": [  
      "AYUNTAMIENTOS"  
    ]  
  },  
  "@context": [  
    "https://smart-data-models.github.io/dataModel.SDG/context.jsonld"  
  ]  
}  
```  
</details><!-- /80-Examples -->    
<!-- 90-FooterNotes -->    
<!-- /90-FooterNotes -->    
<!-- 95-Units -->    
Siehe [FAQ 10] (https://smartdatamodels.org/index.php/faqs/), um eine Antwort auf die Frage zu erhalten, wie man mit Größeneinheiten umgeht    
<!-- /95-Units -->    
<!-- 97-LastFooter -->    
---    
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->    
