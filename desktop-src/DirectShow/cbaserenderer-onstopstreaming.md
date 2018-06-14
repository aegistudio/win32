---
Description: The OnStopStreaming method is called when the filter stops streaming.
ms.assetid: d882fec8-09e1-4d36-a09c-44568e743da3
title: CBaseRenderer.OnStopStreaming method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CBaseRenderer.OnStopStreaming method

The `OnStopStreaming` method is called when the filter stops streaming.

## Syntax


```C++
virtual HRESULT OnStopStreaming();
```



## Parameters

This method has no parameters.

## Return value

Returns S\_OK.

## Remarks

The [**CBaseRenderer::StopStreaming**](cbaserenderer-stopstreaming.md) method calls this method. It does nothing in the base class, but the derived class can override it.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Renbase.h (include Streams.h)</dt> </dl>                                                                                   |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CBaseRenderer Class**](cbaserenderer.md)
</dt> </dl>

 

 



