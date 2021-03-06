---
title: ISCSI\_Persistent\_Login WMI Class
description: ISCSI\_Persistent\_Login WMI Class
ms.assetid: ad00e6ed-adfa-4888-9386-51f937a278d8
---

# ISCSI\_Persistent\_Login WMI Class


## <span id="ddk_iscsi_persistent_login_wmi_class_kr"></span><span id="DDK_ISCSI_PERSISTENT_LOGIN_WMI_CLASS_KR"></span>


The ISCSI\_Persistent\_Login WMI class defines a persistent logon. Miniport drivers that manage iSCSI initiators automatically establish persistent logon connections as soon as they are loaded into the storage driver stack. This timing guarantees that targets for which the initiator maintains persistent logons will be available to the system as early in the startup process as possible.

The ISCSI\_Persistent\_Login class is unpublished and is defined in *Operations.mof*.

When the WMI tool suite compiles this class definition, it produces the [**ISCSI\_Persistent\_Login**](https://msdn.microsoft.com/library/windows/hardware/ff561553) data structure.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20[storage\storage]:%20ISCSI_Persistent_Login%20WMI%20Class%20%20RELEASE:%20%281/11/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




