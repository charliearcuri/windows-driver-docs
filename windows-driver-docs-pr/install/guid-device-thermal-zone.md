---
title: GUID_DEVICE_THERMAL_ZONE
description: GUID_DEVICE_THERMAL_ZONE
ms.assetid: bbb9abb8-aaff-4f1c-ba8d-96fc5b69676a
keywords: ["GUID_DEVICE_THERMAL_ZONE Device and Driver Installation"]
topic_type:
- apiref
api_name:
- GUID_DEVICE_THERMAL_ZONE
api_location:
- Poclass.h
api_type:
- HeaderDef
---

# GUID_DEVICE_THERMAL_ZONE


The GUID_DEVICE_THERMAL_ZONE [device interface class](https://msdn.microsoft.com/library/windows/hardware/ff541339) is defined for Advanced Configuration and Power Interface (ACPI) thermal zone devices.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Attribute</th>
<th align="left">Setting</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>Identifier</p></td>
<td align="left"><p>GUID_DEVICE_THERMAL_ZONE</p></td>
</tr>
<tr class="even">
<td align="left"><p>Class GUID</p></td>
<td align="left"><p>{4AFA3D51-74A7-11d0-be5e-00A0C9062857}</p></td>
</tr>
</tbody>
</table>

 

Remarks
-------

The system-supplied [ACPI driver](https://msdn.microsoft.com/library/windows/hardware/ff540493) registers an instance of this device interface class to notify the operating system and applications of the presence of thermal zone devices.

For information about supplying WDM [function drivers](https://msdn.microsoft.com/library/windows/hardware/ff546516) for ACPI devices, see [Supporting ACPI Devices](https://msdn.microsoft.com/library/windows/hardware/ff536161).

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p>Header</p></td>
<td align="left">Poclass.h (include Poclass.h)</td>
</tr>
</tbody>
</table>

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bdevinst\devinst%5D:%20GUID_DEVICE_THERMAL_ZONE%20%20RELEASE:%20%2810/9/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




