<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
Entité : Vessel  
===============<!-- /10-Header -->  
<!-- 15-License -->  
[Licence ouverte] (https://github.com/smart-data-models//dataModel.MarineTransport/blob/master/Vessel/LICENSE.md)  
[document généré automatiquement] (https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
Description globale : **Le modèle de données est destiné à fournir des informations sur les navires. Il permet de représenter les propriétés de chaque navire : informations statiques et dynamiques**.  
version : 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## Liste des propriétés  

<sup><sub>[*] S'il n'y a pas de type dans un attribut, c'est parce qu'il pourrait avoir plusieurs types ou différents formats/modèles</sub></sup>.  
- `address[object]`: L'adresse postale  . Model: [https://schema.org/address](https://schema.org/address)- `airDraught[number]`: Tirant d'air (distance entre le sommet du point le plus haut d'un navire et sa ligne de flottaison)  . Model: [http://schema.org/Number](http://schema.org/Number)- `alternateName[string]`: Un nom alternatif pour cet élément  - `areaServed[string]`: La zone géographique où un service ou un article offert est fourni  . Model: [https://schema.org/Text](https://schema.org/Text)- `beam[number]`: Beam of Vessel.  . Model: [https://schema.org/Number](https://schema.org/Number)- `buildingAt[string]`: Date et heure de la construction du navire représentées par un format ISO 8601 UTC.  . Model: [https://schema.org/Text](https://schema.org/Text)- `callSign[string]`: Les indicatifs d'appel maritimes sont des indicatifs d'appel attribués comme identifiants uniques aux navires.  . Model: [https://schema.org/Text](https://schema.org/Text)- `courseOverGround[number]`: Course Over Ground (COG).  . Model: [https://schema.org/Number](https://schema.org/Number)- `createdAt[string]`: Date et heure de création de l'entité représentée par un format ISO 8601 UTC.  . Model: [https://schema.org/Text](https://schema.org/Text)- `dataProvider[string]`: Une séquence de caractères identifiant le fournisseur de l'entité de données harmonisées.  . Model: [https://schema.org/Text](https://schema.org/Text)- `dateCreated[string]`: Horodatage de la création de l'entité. Celui-ci sera généralement attribué par la plateforme de stockage.  - `dateModified[string]`: Horodatage de la dernière modification de l'entité. Il sera généralement attribué par la plateforme de stockage.  - `deadweightTonnage[number]`: Tonnage de port en lourd (DWT).  . Model: [https://schema.org/Number](https://schema.org/Number)- `description[string]`: Une description de cet article  - `destinationPort[string]`: Port de destination (système de codage géographique UN/LOCODE (code des Nations unies pour les lieux de commerce et de transport). https://unece.org/trade/publications/recommendation-ndeg16-united-nations-code-trade-and-transport-locations)  . Model: [https://schema.org/Text](https://schema.org/Text)- `draught[number]`: Tirant d'eau (distance verticale entre la ligne de flottaison et le fond de la coque (quille))  . Model: [http://schema.org/Number](http://schema.org/Number)- `financialOwner[string]`: Propriétaire financier  . Model: [https://schema.org/Text](https://schema.org/Text)- `flagCode[string]`: Code international du pavillon (ISO 3166-1 alfa-2)  . Model: [https://schema.org/Text](https://schema.org/Text)- `grossTonnage[number]`: Tonnage brut (GT).  . Model: [https://schema.org/Number](https://schema.org/Number)- `heading[number]`: Cap du navire (HDG).  . Model: [https://schema.org/Number](https://schema.org/Number)- `id[string]`: Identifiant unique de l'entité  - `imo[number]`: Numéro de l'Organisation maritime internationale (un UID mondial permanent)  . Model: [https://schema.org/Number](https://schema.org/Number)- `length[number]`: Longueur du navire.  . Model: [https://schema.org/Number](https://schema.org/Number)- `location[object]`: Référence Geojson à l'élément. Il peut s'agir d'un point, d'une ligne, d'un polygone, d'un point multiple, d'une ligne multiple ou d'un polygone multiple.  - `manager[string]`: Manager Vessel  . Model: [https://schema.org/Text](https://schema.org/Text)- `maximumDraught[number]`: Tirant d'eau maximum.  . Model: [https://schema.org/Number](https://schema.org/Number)- `mmsi[number]`: Numéro d'identité du service mobile maritime (un UID attribué temporairement, émis par l'État du pavillon actuel de cet objet)  . Model: [https://schema.org/Number](https://schema.org/Number)- `modifiedAt[string]`: Date et heure de la dernière modification de l'entité représentée par un format ISO 8601 UTC.  . Model: [https://schema.org/Text](https://schema.org/Text)- `name[string]`: Nom du navire  . Model: [https://schema.org/Text](https://schema.org/Text)- `navigationStatus[number]`: Enum : 0=Fait route au moteur,1=A l'ancre,2=Non commandé,3=Manœuvrabilité restreinte,4=Contraint par son tirant d'eau,5=Amarré,6=En terre,7=Pêche,8=Fait route au large,9=Réservé pour une modification future du statut de navigation pour HSC,10=Réservé pour une modification future du statut de navigation pour le WIG,11=Réservé pour une utilisation future,12=Réservé pour une utilisation future,13=Réservé pour une utilisation future,14=AIS-SART est actif,15=Non défini (par défaut)'. Statut de la navigation. Format de données AIVDM/AIVDO.  . Model: [http://schema.org/Number](http://schema.org/Number)- `observedAt[string]`: Date et heure de cette observation représentées par un format ISO 8601 UTC.  . Model: [https://schema.org/Text](https://schema.org/Text)- `owner[array]`: Une liste contenant une séquence de caractères codée en JSON référençant les identifiants uniques du ou des propriétaires.  - `ownerVessel[string]`: Propriétaire du navire  . Model: [https://schema.org/Text](https://schema.org/Text)- `photo[string]`: URL de la photo du navire  . Model: [https://schema.org/Text](https://schema.org/Text)- `previousPort[string]`: Port précédent (système de codage géographique UN/LOCODE (code des Nations unies pour les lieux de commerce et de transport). https://unece.org/trade/publications/recommendation-ndeg16-united-nations-code-trade-and-transport-locations)  . Model: [https://schema.org/Text](https://schema.org/Text)- `rateOfTurn[number]`: Taux de rotation (ROT).  . Model: [https://schema.org/Number](https://schema.org/Number)- `seeAlso[*]`: liste d'uri pointant vers des ressources supplémentaires sur l'élément  - `source[string]`: Une séquence de caractères donnant la source originale des données de l'entité sous forme d'URL. Il est recommandé d'utiliser le nom de domaine entièrement qualifié du fournisseur source ou l'URL de l'objet source.  - `speedOverGround[number]`: Vitesse au sol (SOG).  . Model: [https://schema.org/Number](https://schema.org/Number)- `technicalManager[string]`: Directeur technique  . Model: [https://schema.org/Text](https://schema.org/Text)- `toBow[number]`: Dimension à l'arc.  . Model: [http://schema.org/Number](http://schema.org/Number)- `toPort[number]`: Dimension au port.  . Model: [http://schema.org/Number](http://schema.org/Number)- `toStardboard[number]`: Dimension à tribord.  . Model: [http://schema.org/Number](http://schema.org/Number)- `toStern[number]`: Dimension à Stern.  . Model: [http://schema.org/Number](http://schema.org/Number)- `type[string]`: Type d'entité NGSI. Il doit s'agir de Vessel  - `vesselSubType[number]`: Enum : 0=Non disponible (par défaut),1-19=Réservé pour une utilisation future,20=Aile au sol (WIG), tous les navires de ce type,21=Aile au sol (WIG), catégorie dangereuse A,22=Aile au sol (WIG), Catégorie dangereuse B,23=Aile au sol (WIG), Catégorie dangereuse C,24=Aile au sol (WIG), Catégorie dangereuse D,25-29=Aile au sol (WIG), Réservé pour une utilisation future,30=Pêche,31=Avitaillement,32=Avitaillement : la longueur dépasse 200m ou la largeur dépasse 25m,33=Dragage ou opérations sous-marines,34=Opérations de plongée,35=Opérations militaires,36=Voile,37=Bateaux de plaisance,38-39=Réservé,40=Bateaux à grande vitesse (BGV), tous les navires de ce type,41=Bateaux à grande vitesse (BGV), catégorie de danger A,42=Bateaux à grande vitesse (BGV), catégorie de danger B,43=Bateaux à grande vitesse (BGV), catégorie de danger C,44=High speed craft (HSC), Hazardous category D,45-48=High speed craft (HSC), Reserved for future use,49=High speed craft (HSC), No additional information,50=Bateau pilote,51=Bateau de recherche et de sauvetage,52=Tug,53=Tender portuaire,54=Equipement anti-pollution,55=Law Enforcement,56-57=Bateau local de rechange,58=Transport médical,59=Navire non-combattant selon la Résolution No. 18,60=Passagers, tous les navires de ce type,61=Passagers, catégorie dangereuse A,62=Passagers, catégorie dangereuse B,63=Passagers, catégorie dangereuse C,64=Passagers, catégorie dangereuse D,65-68=Passagers, Réservé pour utilisation future,69=Passagers, Pas d'information supplémentaire,70=Cargo, tous les navires de ce type,71=Cargo, catégorie dangereuse A,72=Cargo, catégorie dangereuse B,73=Cargo, catégorie dangereuse C,74=Cargo, catégorie dangereuse D,75-78=Cargo, Réservé pour une utilisation future,79=Cargo, Pas d'information supplémentaire,80=Tanker, tous les navires de ce type,81=Citerne, catégorie dangereuse A,82=Citerne, catégorie dangereuse B,83=Citerne, catégorie dangereuse C,84=Citerne, catégorie dangereuse D,85-88=Citerne, Réservé pour une utilisation future,89=Citerne, Pas d'information supplémentaire,90=Autre Type, tous les navires de ce type,91=Autre type, catégorie dangereuse A,92=Autre type, catégorie dangereuse B,93=Autre type, catégorie dangereuse C,94=Autre type, catégorie dangereuse D,95-98=Autre type, réservé pour une utilisation future,99=Autre type, pas d'information supplémentaire'. Code pour le sous-type de navire  . Model: [https://schema.org/Number](https://schema.org/Number)- `vesselType[number]`: Enum : '1=Reserved,2=Wing In Ground,3=Special Category,4=High-Speed Craft,5=Special Category,6=Passenger,7=Cargo,8=Tanker,9=Other'. Code pour le type de navire  . Model: [https://schema.org/Number](https://schema.org/Number)<!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
Propriétés requises  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## Description des propriétés du modèle de données  
Classés par ordre alphabétique (cliquez pour plus de détails)  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
Vessel:    
  description: 'The data model is intended to provide information about vessels. It allows to represent the properties of each vessel: static and dynamic information'    
  properties:    
    address:    
      description: 'The mailing address'    
      properties:    
        addressCountry:    
          description: 'Property. The country. For example, Spain. Model:''https://schema.org/addressCountry'''    
          type: string    
        addressLocality:    
          description: 'Property. The locality in which the street address is, and which is in the region. Model:''https://schema.org/addressLocality'''    
          type: string    
        addressRegion:    
          description: 'Property. The region in which the locality is, and which is in the country. Model:''https://schema.org/addressRegion'''    
          type: string    
        postOfficeBoxNumber:    
          description: 'Property. The post office box number for PO box addresses. For example, 03578. Model:''https://schema.org/postOfficeBoxNumber'''    
          type: string    
        postalCode:    
          description: 'Property. The postal code. For example, 24004. Model:''https://schema.org/https://schema.org/postalCode'''    
          type: string    
        streetAddress:    
          description: 'Property. The street address. Model:''https://schema.org/streetAddress'''    
          type: string    
      type: object    
      x-ngsi:    
        model: https://schema.org/address    
        type: Property    
    airDraught:    
      description: 'Air Draught (distance from the top of a vessel''''s highest point to its waterline)'    
      type: number    
      x-ngsi:    
        model: http://schema.org/Number    
        type: Property    
        units: ' meters'    
    alternateName:    
      description: 'An alternative name for this item'    
      type: string    
      x-ngsi:    
        type: Property    
    areaServed:    
      description: 'The geographic area where a service or offered item is provided'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    beam:    
      description: 'Beam of Vessel.'    
      maximum: 1000    
      minimum: 0    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' meters'    
    buildingAt:    
      description: 'Date and time of building of the vessel represented by an ISO 8601 UTC format.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    callSign:    
      description: 'Maritime call signs are call signs assigned as unique identifiers to vessels'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    courseOverGround:    
      description: 'Course Over Ground (COG).'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' degree'    
    createdAt:    
      description: 'Date and time of creation of the entity represented by an ISO 8601 UTC format.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    dataProvider:    
      description: 'A sequence of characters identifying the provider of the harmonised data entity'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    dateCreated:    
      description: 'Entity creation timestamp. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    dateModified:    
      description: 'Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    deadweightTonnage:    
      description: 'Deadweight Tonnage (DWT).'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' tons'    
    description:    
      description: 'A description of this item'    
      type: string    
      x-ngsi:    
        type: Property    
    destinationPort:    
      description: 'Destination Port (Geographic coding scheme UN/LOCODE (United Nations Code for Trade and Transport Locations). https://unece.org/trade/publications/recommendation-ndeg16-united-nations-code-trade-and-transport-locations)'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    draught:    
      description: 'Draught (vertical distance between the waterline and the bottom of the hull (keel))'    
      type: number    
      x-ngsi:    
        model: http://schema.org/Number    
        type: Property    
        units: ' meters'    
    financialOwner:    
      description: 'Financial Owner'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    flagCode:    
      description: 'International Flag Code (ISO 3166-1 alfa-2)'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    grossTonnage:    
      description: 'Gross Tonnage (GT).'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' moorson tons'    
    heading:    
      description: 'Heading of the Vessel (HDG).'    
      maximum: 511    
      minimum: 0    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' degree'    
    id:    
      description: 'Unique identifier of the entity'    
      type: string    
      x-ngsi:    
        type: Property    
    imo:    
      description: 'International Maritime Organization Number (a global forever UID)'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    length:    
      description: 'Length of Vessel.'    
      maximum: 8000    
      minimum: 0    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' meters'    
    location:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygoProperty.'    
      properties:    
        coordinates:    
          items:    
            type: number    
          type: array    
        type:    
          type: string    
      type: object    
      x-ngsi:    
        type: Geoproperty    
    manager:    
      description: 'Manager Vessel'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    maximumDraught:    
      description: 'Maximum Draught.'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' meters'    
    mmsi:    
      description: 'Marine Mobile Service Identity Number (a temporarily assigned UID, issued by that object''s current flag state)'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    modifiedAt:    
      description: 'Date and time of last modification of the entity represented by an ISO 8601 UTC format.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    name:    
      description: 'Vessel Name'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    navigationStatus:    
      description: 'Enum: ''0=Under way using engine,1=At anchor,2=Not under command,3=Restricted manoeuverability,4=Constrained by her draught,5=Moored,6=Aground,7=Engaged in Fishing,8=Under way sailing,9=Reserved for future amendment of Navigational Status for HSC,10=Reserved for future amendment of Navigational Status for WIG,11=Reserved for future use,12=Reserved for future use,13=Reserved for future use,14=AIS-SART is active,15=Not defined (default)''. Navigation Status. AIVDM/AIVDO data format.'    
      enum:    
        - 0    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
        - 6    
        - 7    
        - 8    
        - 9    
        - 10    
        - 11    
        - 12    
        - 13    
        - 14    
        - 15    
      type: number    
      x-ngsi:    
        model: http://schema.org/Number    
        type: Property    
    observedAt:    
      description: 'Date and time of this observation represented by an ISO 8601 UTC format.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    owner:    
      description: 'A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)'    
      items:    
        anyOf:    
          - description: 'Property. Identifier format of any NGSI entity'    
            maxLength: 256    
            minLength: 1    
            pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
            type: string    
          - description: 'Property. Identifier format of any NGSI entity'    
            format: uri    
            type: string    
        description: 'Property. Unique identifier of the entity'    
      type: array    
      x-ngsi:    
        type: Property    
    ownerVessel:    
      description: 'Owner Vessel'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    photo:    
      description: 'Vessel Photo URL'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    previousPort:    
      description: 'Previous Port (Geographic coding scheme UN/LOCODE (United Nations Code for Trade and Transport Locations). https://unece.org/trade/publications/recommendation-ndeg16-united-nations-code-trade-and-transport-locations)'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    rateOfTurn:    
      description: 'Rate of Turn (ROT).'    
      maximum: 708    
      minimum: 0    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' degree'    
    seeAlso:    
      description: 'list of uri pointing to additional resources about the item'    
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
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: string    
      x-ngsi:    
        type: Property    
    speedOverGround:    
      description: 'Speed Over Ground (SOG).'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
        units: ' meters per second'    
    technicalManager:    
      description: 'Technical Manager'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    toBow:    
      description: 'Dimension to Bow.'    
      type: number    
      x-ngsi:    
        model: http://schema.org/Number    
        type: Property    
        units: ' meters'    
    toPort:    
      description: 'Dimension to Port.'    
      type: number    
      x-ngsi:    
        model: http://schema.org/Number    
        type: Property    
        units: ' meters'    
    toStardboard:    
      description: 'Dimension to Starboard.'    
      type: number    
      x-ngsi:    
        model: http://schema.org/Number    
        type: Property    
        units: ' meters'    
    toStern:    
      description: 'Dimension to Stern.'    
      type: number    
      x-ngsi:    
        model: http://schema.org/Number    
        type: Property    
        units: ' meters'    
    type:    
      description: 'NGSI Entity type. It has to be Vessel'    
      enum:    
        - Vessel    
      type: string    
      x-ngsi:    
        type: Property    
    vesselSubType:    
      description: 'Enum: ''0=Not available (default),1-19=Reserved for future use,20=Wing in ground (WIG), all ships of this type,21=Wing in ground (WIG), Hazardous category A,22=Wing in ground (WIG), Hazardous category B,23=Wing in ground (WIG), Hazardous category C,24=Wing in ground (WIG), Hazardous category D,25-29=Wing in ground (WIG), Reserved for future use,30=Fishing,31=Towing,32=Towing: length exceeds 200m or breadth exceeds 25m,33=Dredging or underwater ops,34=Diving ops,35=Military ops,36=Sailing,37=Pleasure Craft,38-39=Reserved,40=High speed craft (HSC), all ships of this type,41=High speed craft (HSC), Hazardous category A,42=High speed craft (HSC), Hazardous category B,43=High speed craft (HSC), Hazardous category C,44=High speed craft (HSC), Hazardous category D,45-48=High speed craft (HSC), Reserved for future use,49=High speed craft (HSC), No additional information,50=Pilot Vessel,51=Search and Rescue vessel,52=Tug,53=Port Tender,54=Anti-pollution equipment,55=Law Enforcement,56-57=Spare - Local Vessel,58=Medical Transport,59=Noncombatant ship according to RR Resolution No. 18,60=Passenger, all ships of this type,61=Passenger, Hazardous category A,62=Passenger, Hazardous category B,63=Passenger, Hazardous category C,64=Passenger, Hazardous category D,65-68=Passenger, Reserved for future use,69=Passenger, No additional information,70=Cargo, all ships of this type,71=Cargo, Hazardous category A,72=Cargo, Hazardous category B,73=Cargo, Hazardous category C,74=Cargo, Hazardous category D,75-78=Cargo, Reserved for future use,79=Cargo, No additional information,80=Tanker, all ships of this type,81=Tanker, Hazardous category A,82=Tanker, Hazardous category B,83=Tanker, Hazardous category C,84=Tanker, Hazardous category D,85-88=Tanker, Reserved for future use,89=Tanker, No additional information,90=Other Type, all ships of this type,91=Other Type, Hazardous category A,92=Other Type, Hazardous category B,93=Other Type, Hazardous category C,94=Other Type, Hazardous category D,95-98=Other Type, Reserved for future use,99=Other Type, no additional information''. Code for vessel Sub-Type'    
      enum:    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
        - 6    
        - 7    
        - 8    
        - 9    
        - 10    
        - 11    
        - 12    
        - 13    
        - 14    
        - 15    
        - 16    
        - 17    
        - 18    
        - 19    
        - 20    
        - 21    
        - 22    
        - 23    
        - 24    
        - 25    
        - 26    
        - 27    
        - 28    
        - 29    
        - 30    
        - 31    
        - 32    
        - 33    
        - 34    
        - 35    
        - 36    
        - 37    
        - 38    
        - 39    
        - 40    
        - 41    
        - 42    
        - 43    
        - 44    
        - 45    
        - 46    
        - 47    
        - 48    
        - 49    
        - 50    
        - 51    
        - 52    
        - 53    
        - 54    
        - 55    
        - 56    
        - 57    
        - 58    
        - 59    
        - 60    
        - 61    
        - 62    
        - 63    
        - 64    
        - 65    
        - 66    
        - 67    
        - 68    
        - 69    
        - 70    
        - 71    
        - 72    
        - 73    
        - 74    
        - 75    
        - 76    
        - 77    
        - 78    
        - 79    
        - 80    
        - 81    
        - 82    
        - 83    
        - 84    
        - 85    
        - 86    
        - 87    
        - 88    
        - 89    
        - 90    
        - 91    
        - 92    
        - 93    
        - 94    
        - 95    
        - 96    
        - 97    
        - 98    
        - 99    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
    vesselType:    
      description: 'Enum: ''1=Reserved,2=Wing In Ground,3=Special Category,4=High-Speed Craft,5=Special Category,6=Passenger,7=Cargo,8=Tanker,9=Other''. Code for vessel type'    
      enum:    
        - 1    
        - 2    
        - 3    
        - 4    
        - 5    
        - 6    
        - 7    
        - 8    
        - 9    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
        type: Property    
  required:    
    - id    
    - type    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2022 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.MarineTransport/blob/master/Vessel/LICENSE.md    
  x-model-schema: https://gitlab.com/hiades/fiware/smart-data-models/-/raw/main/dataModel.Vessel/schema.json    
  x-model-tags: ""    
  x-version: 0.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## Exemples de charges utiles  
#### Vessel NGSI-v2 key-values Exemple  
Voici un exemple de vaisseau au format JSON-LD en tant que valeurs-clés. Ceci est compatible avec NGSI-v2 quand on utilise `options=keyValues` et renvoie les données contextuelles d'une entité individuelle.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:mrn:amura:vessel:test",  
    "type": "Vessel",  
    "location": {  
        "type": "Point",  
        "coordinates": [  
            -5.993307,  
            37.362882  
        ]  
    },  
    "imo": 9863637,  
    "mmsi": 210049000,  
    "callSign": "5BPC5",  
    "name": "ELEANOR ROOSEVELT",  
    "speedOverGround": 1,  
    "courseOverGround": 1,  
    "heading": 1,  
    "rateOfTurn": 1,  
    "createdAt": "2022-06-01T07:00:00.00Z",  
    "modifiedAt": "2022-06-01T07:00:00.00Z",  
    "observedAt": "2022-06-01T07:00:00.00Z",  
    "flagCode": "CY",  
    "vesselType": 1,  
    "vesselSubType": 2,  
    "grossTonnage": 12467,  
    "beam": 7,  
    "length": 32,  
    "maximumDraught": 5,  
    "deadweightTonnage": 8,  
    "buildingAt": "2021-01-01T07:00:00.00Z",  
    "toBow": 3,  
    "toStern": 20,  
    "toPort": 17,  
    "toStardboard": 4,  
    "navigationStatus": 4,  
    "airDraught": 4,  
    "draught": 4,  
    "photo": "PHOTO URL",  
    "ownerVessel": "OWNER NAME",  
    "manager": "MANAGER NAME",  
    "financialOwner": "FINANCIAL OWNER NAME",  
    "technicalManager": "TECHNICAL MANAGER NAME",  
    "dataProvider": "AIS",  
    "destinationPort": "ESVLC",  
    "previousPort": "ESPMI"  
}  
```  
</details>  
#### Vaisseau NGSI-v2 normalisé Exemple  
Voici un exemple de Navire au format JSON-LD tel que normalisé. Ce format est compatible avec NGSI-v2 lorsqu'il n'utilise pas d'options et renvoie les données contextuelles d'une entité individuelle.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:mrn:amura:vessel:test",  
    "type": "Vessel",  
    "location": {  
        "type": "geo:json",  
        "value": {  
            "type": "Point",  
            "coordinates": [  
                -5.993307,  
                37.362882  
            ]  
        }  
    },  
    "imo": {  
        "type": "Number",  
        "value": 9863637  
    },  
    "mmsi": {  
        "type": "Number",  
        "value": 210049000  
    },  
    "callSign": {  
        "type": "Text",  
        "value": "5BPC5"  
    },  
    "name": {  
        "type": "Text",  
        "value": "ELEANOR ROOSEVELT"  
    },  
    "speedOverGround": {  
        "type": "Number",  
        "value": 1  
    },  
    "courseOverGround": {  
        "type": "Number",  
        "value": 1  
    },  
    "heading": {  
        "type": "Number",  
        "value": 1  
    },  
    "rateOfTurn": {  
        "type": "Number",  
        "value": 1  
    },  
    "createdAt": {  
        "type": "DateTime",  
        "value": "2022-06-01T07:00:00.00Z"  
    },  
    "modifiedAt": {  
        "type": "DateTime",  
        "value": "2022-06-01T07:00:00.00Z"  
    },  
    "observedAt": {  
        "type": "DateTime",  
        "value": "2022-06-01T07:00:00.00Z"  
    },  
    "flagCode": {  
        "type": "Text",  
        "value": "CY"  
    },  
    "vesselType": {  
        "type": "Number",  
        "value": 1  
    },  
    "vesselSubType": {  
        "type": "Number",  
        "value": 2  
    },  
    "grossTonnage": {  
        "type": "Number",  
        "value": 12467  
    },  
    "beam": {  
        "type": "Number",  
        "value": 7  
    },  
    "length": {  
        "type": "Number",  
        "value": 32  
    },  
    "maximumDraught": {  
        "type": "Number",  
        "value": 5  
    },  
    "deadweightTonnage": {  
        "type": "Number",  
        "value": 8  
    },  
    "buildingAt": {  
        "type": "DateTime",  
        "value": "2021-01-01T07:00:00.00Z1"  
    },  
    "toBow": {  
        "type": "Number",  
        "value": 3  
    },  
    "toStern": {  
        "type": "Number",  
        "value": 20  
    },  
    "toPort": {  
        "type": "Number",  
        "value": 17  
    },  
    "toStardboard": {  
        "type": "Number",  
        "value": 4  
    },  
    "navigationStatus": {  
        "type": "Number",  
        "value": 4  
    },  
    "airDraught": {  
        "type": "Number",  
        "value": 4  
    },  
    "draught": {  
        "type": "Number",  
        "value": 4  
    },  
    "photo": {  
        "type": "Text",  
        "value": "URL PHOTO"  
    },  
    "ownerVessel": {  
        "type": "Text",  
        "value": "OWNER NAME"  
    },  
    "manager": {  
        "type": "Text",  
        "value": "MANAGER NAME"  
    },  
    "financialOwner": {  
        "type": "Text",  
        "value": "FINANCIAL OWNER NAME"  
    },  
    "technicalManager": {  
        "type": "Text",  
        "value": "TECHNICAL MANAGER NAME"  
    },  
    "dataProvider": {  
        "type": "Text",  
        "value": "AIS"  
    },  
    "destinationPort": {  
        "type": "Text",  
        "value": "ESVLC"  
    },  
    "previousPort": {  
        "type": "Text",  
        "value": "ESPMI"  
    }  
}  
```  
</details>  
#### Vessel NGSI-LD key-values Exemple  
Voici un exemple de vaisseau au format JSON-LD en tant que valeurs-clés. Ceci est compatible avec NGSI-LD quand on utilise `options=keyValues` et renvoie les données contextuelles d'une entité individuelle.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:mrn:amura:vessel:test",  
    "type": "Vessel",  
    "location": {  
        "type": "Point",  
        "coordinates": [  
            -5.993307,  
            37.362882  
        ]  
    },  
    "imo": 9863637,  
    "mmsi": 210049000,  
    "callSign": "5BPC5",  
    "name": "ELEANOR ROOSEVELT",  
    "speedOverGround": 1,  
    "courseOverGround": 1,  
    "heading": 1,  
    "rateOfTurn": 1,  
    "createdAt": "2022-06-01T07:00:00.00Z",  
    "modifiedAt": "2022-06-01T07:00:00.00Z",  
    "observedAt": "2022-06-01T07:00:00.00Z",  
    "flagCode": "CY",  
    "vesselType": 1,  
    "vesselSubType": 2,  
    "grossTonnage": 12467,  
    "beam": 7,  
    "length": 32,  
    "maximumDraught": 5,  
    "deadweightTonnage": 8,  
    "buildingAt": "2021-01-01T07:00:00.00Z",  
    "toBow": 3,  
    "toStern": 20,  
    "toPort": 17,  
    "toStardboard": 4,  
    "navigationStatus": 4,  
    "airDraught": 4,  
    "draught": 4,  
    "photo": "PHOTO URL",  
    "ownerVessel": "OWNER NAME",  
    "manager": "MANAGER NAME",  
    "financialOwner": "FINANCIAL OWNER NAME",  
    "technicalManager": "TECHNICAL MANAGER NAME",  
    "dataProvider": "AIS",  
    "destinationPort": "ESVLC",  
    "previousPort": "ESPMI",  
    "@context": [  
        "https://gitlab.com/hiades/fiware/smart-data-models/-/raw/main/context.jsonld",  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.MarineTransport/master/context.jsonld"  
    ]  
}  
```  
</details>  
#### Vaisseau NGSI-LD normalisé Exemple  
Voici un exemple de Navire au format JSON-LD tel que normalisé. Ce format est compatible avec NGSI-LD lorsqu'il n'utilise pas d'options et renvoie les données contextuelles d'une entité individuelle.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:mrn:amura:vessel:test",  
    "type": "Vessel",  
    "location": {  
        "type": "GeoProperty",  
        "value": {  
            "type": "Point",  
            "coordinates": [  
                -5.993307,  
                37.362882  
            ]  
        }  
    },  
    "imo": {  
        "type": "Property",  
        "value": 9863637  
    },  
    "mmsi": {  
        "type": "Property",  
        "value": 210049000  
    },  
    "callSign": {  
        "type": "Property",  
        "value": "5BPC5"  
    },  
    "name": {  
        "type": "Property",  
        "value": "ELEANOR ROOSEVELT"  
    },  
    "speedOverGround": {  
        "type": "Property",  
        "value": 1  
    },  
    "courseOverGround": {  
        "type": "Property",  
        "value": 1  
    },  
    "heading": {  
        "type": "Property",  
        "value": 1  
    },  
    "rateOfTurn": {  
        "type": "Property",  
        "value": 1  
    },  
    "createdAt": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2022-06-01T07:00:00.00Z"  
        }  
    },  
    "modifiedAt": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2022-06-01T07:00:00.00Z"  
        }  
    },  
    "observedAt": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2022-06-01T07:00:00.00Z"  
        }  
    },  
    "flagCode": {  
        "type": "Property",  
        "value": "CY"  
    },  
    "vesselType": {  
        "type": "Property",  
        "value": 1  
    },  
    "vesselSubType": {  
        "type": "Property",  
        "value": 2  
    },  
    "grossTonnage": {  
        "type": "Property",  
        "value": 12467  
    },  
    "beam": {  
        "type": "Property",  
        "value": 7  
    },  
    "length": {  
        "type": "Property",  
        "value": 32  
    },  
    "maximumDraught": {  
        "type": "Property",  
        "value": 5  
    },  
    "deadweightTonnage": {  
        "type": "Property",  
        "value": 8  
    },  
    "buildingAt": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-01-01T07:00:00.00Z1"  
        }  
    },  
    "toBow": {  
        "type": "Property",  
        "value": 3  
    },  
    "toStern": {  
        "type": "Property",  
        "value": 20  
    },  
    "toPort": {  
        "type": "Property",  
        "value": 17  
    },  
    "toStardboard": {  
        "type": "Property",  
        "value": 4  
    },  
    "navigationStatus": {  
        "type": "Property",  
        "value": 4  
    },  
    "airDraught": {  
        "type": "Property",  
        "value": 4  
    },  
    "draught": {  
        "type": "Property",  
        "value": 4  
    },  
    "photo": {  
        "type": "Property",  
        "value": "URL PHOTO"  
    },  
    "ownerVessel": {  
        "type": "Property",  
        "value": "OWNER NAME"  
    },  
    "manager": {  
        "type": "Property",  
        "value": "MANAGER NAME"  
    },  
    "financialOwner": {  
        "type": "Property",  
        "value": "FINANCIAL OWNER NAME"  
    },  
    "technicalManager": {  
        "type": "Property",  
        "value": "TECHNICAL MANAGER NAME"  
    },  
    "dataProvider": {  
        "type": "Property",  
        "value": "AIS"  
    },  
    "destinationPort": {  
        "type": "Property",  
        "value": "ESVLC"  
    },  
    "previousPort": {  
        "type": "Property",  
        "value": "ESPMI"  
    },  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.MarineTransport/master/context.jsonld"  
    ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
Voir [FAQ 10](https://smartdatamodels.org/index.php/faqs/) pour obtenir une réponse sur la façon de traiter les unités de magnitude.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
