---
Description: Verifies whether the referenced physical element can be contained by, or inserted into, the physical package.
ms.assetid: 406aaa75-b48c-4377-adb5-e900676b6e36
ms.tgt_platform: multiple
title: IsCompatible method of the CIM_PhysicalPackage class
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CIM_PhysicalPackage.IsCompatible
api_type: 
- COM
api_location: 
- CIMWin32.dll
---

# IsCompatible method of the CIM\_PhysicalPackage class

The **IsCompatible** method verifies whether the referenced physical element can be contained by, or inserted into, the physical package. In a subclass, the set of possible return codes can be specified by using a **ValueMap** qualifier on the method. The strings to which the **ValueMap** contents are translated can also be specified in the subclass as a **Values** array qualifier.

> [!IMPORTANT]
> The DMTF (Distributed Management Task Force) CIM (Common Information Model) classes are the parent classes upon which WMI classes are built. WMI currently supports only the [CIM 2.x version schemas](https://Go.Microsoft.Com/FWLink/p/?LinkID=309367).

 

This topic uses Managed Object Format (MOF) syntax. For more information about using this method, see [Calling a Method](https://docs.microsoft.com/windows/desktop/WmiSdk/calling-a-method).

## Syntax


```mof
uint32 IsCompatible(
  [in] CIM_PhysicalElement REF ElementToCheck
);
```



## Parameters

<dl> <dt>

*ElementToCheck* \[in\]
</dt> <dd>

Reference to the physical element that the **IsCompatible** method runs against.

</dd> </dl>

## Return value

Returns a value of 0 (zero) on success, and any other number to indicate an error.

## Remarks

This method is currently not implemented by WMI. To use this method, you must implement it in your own provider.

This documentation is derived from the CIM class descriptions published by the DMTF. Microsoft may have made changes to correct minor errors, conform to Microsoft SDK documentation standards, or provide more information.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                          |
| Namespace<br/>                | Root\\CIMV2<br/>                                                                  |
| MOF<br/>                      | <dl> <dt>CIMWin32.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>CIMWin32.dll</dt> </dl> |



## See also

<dl> <dt>

[**CIM\_PhysicalPackage**](iscompatible-method-in-class-cim-physicalpackage.md)
</dt> <dt>

[**CIM\_PhysicalPackage**](cim-physicalpackage.md)
</dt> </dl>

 

 




