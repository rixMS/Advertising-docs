---
title: ImportEntityType Value Set - Campaign Management
ms.service: bing-ads-campaign-management-service
ms.topic: article
author: eric-urban
ms.author: eur
description: Defines the supported import entity types.
---
# ImportEntityType Value Set - Campaign Management
Defines the supported import entity types.

## Syntax
```xml
<xs:simpleType name="ImportEntityType" xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:restriction base="xs:string">
    <xs:enumeration value="Unknown" />
    <xs:enumeration value="Campaign" />
    <xs:enumeration value="AdGroup" />
    <xs:enumeration value="Ad" />
    <xs:enumeration value="Keyword" />
  </xs:restriction>
</xs:simpleType>
```

## <a name="values"></a>Values

The [ImportEntityType](importentitytype.md) value set has the following values: [Ad](#ad), [AdGroup](#adgroup), [Campaign](#campaign), [Keyword](#keyword), [Unknown](#unknown).

|Value|Description|
|-----------|---------------|
|<a name="ad"></a>Ad|Reserved.|
|<a name="adgroup"></a>AdGroup|Reserved.|
|<a name="campaign"></a>Campaign|The import entity is a campaign.|
|<a name="keyword"></a>Keyword|Reserved.|
|<a name="unknown"></a>Unknown|Reserved for future use.|

## Requirements
Service: [CampaignManagementService.svc v13](https://campaign.api.bingads.microsoft.com/Api/Advertiser/CampaignManagement/v13/CampaignManagementService.svc)  
Namespace: https\://bingads.microsoft.com/CampaignManagement/v13  

## Used By
[GetImportEntityIdsMapping](getimportentityidsmapping.md)  
