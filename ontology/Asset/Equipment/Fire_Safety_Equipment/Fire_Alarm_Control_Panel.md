[Index](../../../Index.md) > [Asset](../../Asset.md) > [Equipment](../Equipment.md) > [Fire_Safety_Equipment](Fire_Safety_Equipment.md) > [Fire_Alarm_Control_Panel](#)
# Fire_Alarm_Control_Panel

**Display name:** Fire Alarm Control Panel<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Fire_Alarm_Control_Panel;1

---

## Relationships
### Inherited Relationships
* **[Equipment](../Equipment.md):** feeds, isFedBy
* **[Asset](../../Asset.md):** commissionedBy, documentation, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Equipment](../Equipment.md):** operationalStageCount
* **[Asset](../../Asset.md):** assetTag, commissioningDate, customTags, externalIds, geometry, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### Inherited
* [Asset](../../Asset.md).hasPart
* [Asset](../../Asset.md).isPartOf
* [EquipmentCollection](../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).includes