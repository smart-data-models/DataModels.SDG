<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
实体：项目  
=====<!-- /10-Header -->  
<!-- 15-License -->  
[开放许可](https://github.com/smart-data-models//dataModel.SDG/blob/master/Project/LICENSE.md)  
[文件自动生成](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
全球描述：**一系列活动，这些活动的实施有助于实现某个战略目标（提供关键服务、管理改革、与地区密切联系、促进企业发展、重点投资、促进社会/文化/体育发展等）。该目标本身由一个或多个项目组成，并涉及战略计划中的一个战略轴心（工作模式、经济发展、社会发展、环境发展）。  
版本： 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## 属性列表  

<sup><sub>[*] 如果属性中没有类型，是因为它可能有多个类型或不同的格式/模式</sub></sup>。  
- `address[object]`: 邮寄地址  . Model: [https://schema.org/address](https://schema.org/address)	- `addressCountry[string]`: 国家。例如，西班牙  . Model: [https://schema.org/addressCountry](https://schema.org/addressCountry)  
	- `addressLocality[string]`: 街道地址所在的地点，以及该地点所在的区域  . Model: [https://schema.org/addressLocality](https://schema.org/addressLocality)  
	- `addressRegion[string]`: 地点所在的地区，以及该地区位于哪个国家  . Model: [https://schema.org/addressRegion](https://schema.org/addressRegion)  
	- `district[string]`: 地区是一种行政区划，在一些国家由地方政府管理    
	- `postOfficeBoxNumber[string]`: 用于邮政信箱地址的邮政信箱号码。例如：03578  . Model: [https://schema.org/postOfficeBoxNumber](https://schema.org/postOfficeBoxNumber)  
	- `postalCode[string]`: 邮政编码。例如：24004  . Model: [https://schema.org/https://schema.org/postalCode](https://schema.org/https://schema.org/postalCode)  
	- `streetAddress[string]`: 街道地址  . Model: [https://schema.org/streetAddress](https://schema.org/streetAddress)  
- `alternateName[string]`: 该项目的替代名称  - `areaServed[string]`: 提供服务或提供物品的地理区域  . Model: [https://schema.org/Text](https://schema.org/Text)- `axis[string]`: 项目所属的战略轴心  - `challenges[string]`: 项目面临的挑战  - `dataProvider[string]`: 标识统一数据实体提供者的字符序列  - `dateCreated[date-time]`: 实体创建时间戳。通常由存储平台分配  - `dateModified[date-time]`: 实体最后一次修改的时间戳。通常由存储平台分配  - `delegations[array]`: 项目所属的代表团或内部部门  - `delegationsInvolved[array]`: 参与项目的代表团或内部部门  - `description[string]`: 项目描述  - `id[*]`: 实体的唯一标识符  - `interestGroups[array]`: 参与项目的代表团或内部部门  - `location[*]`: 项目的 Geojson 引用。它可以是点、线条字符串、多边形、多点、多线条字符串或多多边形  - `modifications[string]`: 项目在可能的更新中纳入的变化  - `name[string]`: 该项目的名称  - `observations[string]`: 关于项目具体特点的自由文本  - `owner[array]`: 包含一个 JSON 编码字符序列的列表，其中引用了所有者的唯一 Ids  - `plan[string]`: 项目子类型。枚举：'EDS、PPE  - `refDevice[array]`: 用于测量的设备  - `sdg[string]`: 项目所属的可持续发展目标  - `seeAlso[*]`: 指向有关该项目的其他资源的 uri 列表  - `source[string]`: 以 URL 形式给出实体数据原始来源的字符串。建议使用源提供者的完全合格域名或源对象的 URL  - `strategicObjective[string]`: 项目所属的战略目标  - `type[string]`: 必须等于项目  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
所需属性  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## 属性的数据模型描述  
按字母顺序排列（点击查看详情）  
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
## 有效载荷示例  
#### 项目 NGSI-v2 键值示例  
下面是一个以 JSON-LD 格式作为键值的项目示例。当使用 `options=keyValues` 时，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "0.E.6.AY1",  
  "type": "Project",  
  "plan": "EDS",  
  "delegations": ["TRANSFORMATION DIGITAL Y TURISMO"],  
  "delegationsInvolved": [  
    "BIENESTAR SOCIAL",  
    "CONCERTACION Y PARTICIPACION TERRITORIAL"  
  ],  
  "dateCreated": "2016-08-08T10:18:16Z",  
  "dateModified": "2016-08-08T10:18:16Z",  
  "name": "O.E.6.AY1 Plan Smart Provincia",  
  "description": "Realizar un estudio que permita conocer las necesidades de nuevos servicios que a futuro deba prestar la DiputaciOn de Badajoz, de modo que le permita anticiparte y adaptarse a las nuevas necesidades de todos sus grupos de interes. Analizar cmo mejorar el cumplimiento de los ODS por parte de la Diputaci6n con nuevas actuaciones y eliminacion de otras obsoletas ejecutadas por rutina y sin evaluar.",  
  "axisN": "B. DESARROLLO ECONOMICO",  
  "interestGroups": ["AYUNTAMIENTOS"]  
}  
```  
</details>  
#### 项目 NGSI-v2 标准化示例  
下面是一个规范化 JSON-LD 格式的项目示例。在不使用选项的情况下，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
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
    "type": "array",  
    "value": [  
      "TRANSFORMATION DIGITAL Y TURISMO"  
    ]  
  },  
  "delegationsInvolved": {  
    "type": "array",  
    "value": [  
      "BIENESTAR SOCIAL",  
      "CONCERTACION Y PARTICIPACION TERRITORIAL"  
    ]  
  },  
  "dateCreated": {  
    "type": "Date-Time",  
    "value": "2016-08-08T10:18:16Z"  
  },  
  "dateModified": {  
    "type": "Date-Time",  
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
    "type": "Text",  
    "value": [  
      "AYUNTAMIENTOS"  
    ]  
  }  
}  
```  
</details>  
#### 项目 NGSI-LD 键值示例  
下面是一个以 JSON-LD 格式作为键值的项目示例。当使用 `options=keyValues` 时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
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
#### 项目 NGSI-LD 标准化示例  
下面是一个规范化 JSON-LD 格式的项目示例。在不使用选项时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
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
请参阅 [FAQ 10](https://smartdatamodels.org/index.php/faqs/)，获取如何处理幅度单位的答案。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
