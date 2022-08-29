[Index](../../../../Index.md) > [Point](../../../Point.md) > [Status](../../Status.md) > [Mode_Status](../Mode_Status.md) > [Unoccupied_Mode_Status](Unoccupied_Mode_Status.md) > [Unoccupied_Cooling_Mode_Status](#)
# Unoccupied_Cooling_Mode_Status

**Display name:** Unoccupied Cooling Mode Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Unoccupied_Cooling_Mode_Status;1

---

## Relationships
### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf

---

## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Point](../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint