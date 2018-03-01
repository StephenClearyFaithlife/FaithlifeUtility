# StreamUtility.ReadBlock method

Reads *count* bytes from *stream* into *buffer*, starting at the byte given by *offset*.

```csharp
public static int ReadBlock(this Stream stream, byte[] buffer, int offset, int count)
```

| parameter | description |
| --- | --- |
| stream | The stream to read from. |
| buffer | The buffer to read data into. |
| offset | The offset within the buffer at which data is first written. |
| count | The count of bytes to read. |

## Remarks

Unlike Stream.Read, this method will not return fewer bytes than requested unless the end of the stream is reached.

## See Also

* class [StreamUtility](../StreamUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->