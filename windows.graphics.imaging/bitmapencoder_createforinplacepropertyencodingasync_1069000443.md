---
-api-type: winrt method
---
 You can only use these methods on the encoder:
 The input [BitmapDecoder](bitmapdecoder.md) must be an encoder created on a stream with [ReadWrite](../windows.storage/fileaccessmode.md) access.
 Not all metadata formats support fast metadata encoding. The native metadata handlers that support metadata are IFD, Exif, XMP, and GPS.
 The metadata block must have enough padding to store the properties that you are trying to edit.