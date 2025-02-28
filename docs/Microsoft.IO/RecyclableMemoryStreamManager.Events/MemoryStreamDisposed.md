# RecyclableMemoryStreamManager.Events.MemoryStreamDisposed method

Logged when the stream is disposed.

```csharp
public void MemoryStreamDisposed(Guid guid, string tag, string allocationStack, string disposeStack)
```

| parameter | description |
| --- | --- |
| guid | A unique ID for this stream. |
| tag | A temporary ID for this stream, usually indicates current usage. |
| allocationStack | Call stack of initial allocation. |
| disposeStack | Call stack of the dispose. |

## See Also

* class [Events](../RecyclableMemoryStreamManager.Events.md)
* namespace [Microsoft.IO](../../Microsoft.IO.RecyclableMemoryStream.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.IO.RecyclableMemoryStream.dll -->
