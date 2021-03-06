---
Description: The EffectGetPriority method retrieves the effect's priority level. For a given object, the render engine applies effects in order of priority, starting with priority level zero.
ms.assetid: 2504fa0c-f052-4d99-98c3-803b0c0d49e5
title: IAMTimelineEffect::EffectGetPriority method (Qedit.h)
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IAMTimelineEffect.EffectGetPriority
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
---

# IAMTimelineEffect::EffectGetPriority method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `EffectGetPriority` method retrieves the effect's priority level. For a given object, the render engine applies effects in order of priority, starting with priority level zero.

## Syntax


```C++
HRESULT EffectGetPriority(
   long *pVal
);
```



## Parameters

<dl> <dt>

*pVal* 
</dt> <dd>

Receives the priority level.

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](https://go.microsoft.com/fwlink/p/?linkid=129787). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IAMTimelineEffect Interface**](iamtimelineeffect.md)
</dt> <dt>

[Error and Success Codes](error-and-success-codes.md)
</dt> </dl>

 

 




