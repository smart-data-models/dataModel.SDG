<!-- 10-Header -->    
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)    
Entité : Projet    
===============<!-- /10-Header -->    
<!-- 15-License -->    
[Licence ouverte] (https://github.com/smart-data-models//dataModel.SDG/blob/master/Project/LICENSE.md)    
[document généré automatiquement] (https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)    
<!-- /15-License -->    
<!-- 20-Description -->    
Description globale : **Ensemble d'activités qui, lorsqu'elles sont exécutées, contribuent à la réalisation d'un objectif stratégique (fourniture de services clés, évolution de la gestion, contact étroit avec le territoire, stimulation des entreprises, investissements ciblés, promotion sociale/culturelle/sportive, etc.) Cet objectif est lui-même composé d'un ou plusieurs projets et concerne l'un des axes stratégiques (modèle de travail, développement économique, développement social, développement environnemental) qui donnent une forme de haut niveau au plan stratégique**.    
version : 0.0.1    
<!-- /20-Description -->    
<!-- 30-PropertiesList -->    
## Liste des propriétés    
<sup><sub>[*] S'il n'y a pas de type dans un attribut, c'est parce qu'il peut avoir plusieurs types ou différents formats/modèles</sub></sup>.    
- `address[object]`: L'adresse postale  . Model: [https://schema.org/address](https://schema.org/address)	- `addressCountry[string]`: Le pays. Par exemple, l'Espagne  . Model: [https://schema.org/addressCountry](https://schema.org/addressCountry)    
	- `addressLocality[string]`: La localité dans laquelle se trouve l'adresse postale et qui se trouve dans la région  . Model: [https://schema.org/addressLocality](https://schema.org/addressLocality)    
	- `addressRegion[string]`: La région dans laquelle se trouve la localité et qui se trouve dans le pays  . Model: [https://schema.org/addressRegion](https://schema.org/addressRegion)    
	- `district[string]`: Un district est un type de division administrative qui, dans certains pays, est géré par le gouvernement local.      
	- `postOfficeBoxNumber[string]`: Le numéro de la boîte postale pour les adresses de boîtes postales. Par exemple, 03578  . Model: [https://schema.org/postOfficeBoxNumber](https://schema.org/postOfficeBoxNumber)    
	- `postalCode[string]`: Le code postal. Par exemple, 24004  . Model: [https://schema.org/https://schema.org/postalCode](https://schema.org/https://schema.org/postalCode)    
	- `streetAddress[string]`: L'adresse de la rue  . Model: [https://schema.org/streetAddress](https://schema.org/streetAddress)    
	- `streetNr[string]`: Numéro identifiant une propriété spécifique sur une voie publique      
- `alternateName[string]`: Un nom alternatif pour ce poste  - `areaServed[string]`: La zone géographique où un service ou un article est offert  . Model: [https://schema.org/Text](https://schema.org/Text)- `axis[string]`: Axe stratégique dans lequel s'inscrit le projet  - `challenges[string]`: Défis à relever par le projet  - `dataProvider[string]`: Une séquence de caractères identifiant le fournisseur de l'entité de données harmonisées  - `dateCreated[date-time]`: Horodatage de la création de l'entité. Celle-ci est généralement attribuée par la plate-forme de stockage  - `dateModified[date-time]`: Date de la dernière modification de l'entité. Cette date est généralement attribuée par la plate-forme de stockage  - `delegations[array]`: Délégations ou services internes auxquels le projet appartient  - `delegationsInvolved[array]`: Délégations ou services internes impliqués dans le projet  - `description[string]`: Une description de l'article  - `id[*]`: Identifiant unique de l'entité  - `interestGroups[array]`: Délégations ou services internes impliqués dans le projet  - `location[*]`: Référence Geojson à l'élément. Il peut s'agir d'un point, d'une chaîne de ligne, d'un polygone, d'un point multiple, d'une chaîne de ligne multiple ou d'un polygone multiple.  - `modifications[string]`: Changements que le projet a intégrés dans une éventuelle mise à jour  - `name[string]`: Le nom de cet élément  - `observations[string]`: Texte libre sur les caractéristiques spécifiques du projet  - `owner[array]`: Une liste contenant une séquence de caractères encodés JSON référençant les identifiants uniques du ou des propriétaires.  - `plan[string]`: Sous-type de projet. Enum : "EDS, PPE  - `refDevice[array]`: Dispositif(s) utilisé(s) pour obtenir la mesure  - `sdg[string]`: Objectif de développement durable auquel le projet appartient  - `seeAlso[*]`: liste d'uri pointant vers des ressources supplémentaires concernant l'élément  - `source[string]`: Séquence de caractères indiquant la source originale des données de l'entité sous forme d'URL. Il est recommandé d'utiliser le nom de domaine complet du fournisseur de la source ou l'URL de l'objet source.  - `strategicObjective[string]`: Objectif stratégique dans lequel s'inscrit le projet  - `type[string]`: Il doit être égal à Projet  <!-- /30-PropertiesList -->    
<!-- 35-RequiredProperties -->    
Propriétés requises    
- `id`  - `type`  <!-- /35-RequiredProperties -->    
<!-- 40-RequiredProperties -->    
<!-- /40-RequiredProperties -->    
<!-- 50-DataModelHeader -->    
## Modèle de données description des propriétés    
Classés par ordre alphabétique (cliquez pour plus de détails)    
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
## Exemples de charges utiles    
#### Projet NGSI-v2 valeurs-clés Exemple    
Voici un exemple de projet au format JSON-LD sous forme de valeurs-clés. Ceci est compatible avec NGSI-v2 lorsque l'on utilise `options=keyValues` et renvoie les données contextuelles d'une entité individuelle.    
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
#### Projet NGSI-v2 normalisé Exemple    
Voici un exemple de projet au format JSON-LD tel qu'il a été normalisé. Ce format est compatible avec NGSI-v2 lorsque les options ne sont pas utilisées et renvoie les données contextuelles d'une entité individuelle.    
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
#### Projet NGSI-LD valeurs clés Exemple    
Voici un exemple de projet au format JSON-LD sous forme de valeurs-clés. Ceci est compatible avec NGSI-LD lorsque l'on utilise `options=keyValues` et renvoie les données contextuelles d'une entité individuelle.    
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
#### Projet NGSI-LD normalisé Exemple    
Voici un exemple de projet au format JSON-LD normalisé. Ce format est compatible avec le format NGSI-LD lorsqu'il n'utilise pas d'options et renvoie les données contextuelles d'une entité individuelle.    
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
Voir [FAQ 10] (https://smartdatamodels.org/index.php/faqs/) pour obtenir une réponse à la question de savoir comment traiter les unités de magnitude.    
<!-- /95-Units -->    
<!-- 97-LastFooter -->    
---    
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->    
