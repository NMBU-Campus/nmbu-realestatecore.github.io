[Index](../../../../Index.md) > [Point](../../../Point.md) > [Sensor](../../Sensor.md) > [Temperature_Sensor](../Temperature_Sensor.md) > [Radiant_Panel_Temperature_Sensor](Radiant_Panel_Temperature_Sensor.md) > [Outside_Face_Surface_Temperature_Sensor](#)
# Outside_Face_Surface_Temperature_Sensor

**Display name:** Outside Face Surface Temperature Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Outside_Face_Surface_Temperature_Sensor;1

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