# Changelog

## Version v0.6.0 (2020-05-25)

### Fixes
* Fixed Compression when using ConvertTo-Base64 with a MemoryStream.

### Formatting
* Formatting updates to resolve Script Analyzer errors

## Version v0.5.0 (2020-04-01)

### New functions
* ConvertFrom-Base64ToByteArray
* ConvertFrom-ByteArrayToMemoryStream
* ConvertFrom-MemoryStreamToString

### New Aliases
* ConvertFrom-Base64StringToByteArray -> ConvertFrom-Base64ToByteArray
* ConvertFrom-Base64StringToString -> ConvertFrom-Base64ToString
* ConvertFrom-ByteArrayToBase64String -> ConvertFrom-ByteArrayToBase64

## Version v0.4.1 (2020-04-01)

### ConvertTo-CliXml
* Fixed support for a single string that contains multiple Clixml records.

## Version v0.4.0 (2019-04-27)

### Manifest Updates
* Updated CompatiblePSEditions
* Added PrivateData Tags to indicate platform compatibility

## Version v0.3.5 (2019-03-07)

### ConvertTo-CliXml
* Added Depth parameter to "ConvertTo-CliXml"

## Version v0.2.1.x (2018-08-30)

### ConvertFrom-Base64
* Initial Release

### ConvertFrom-MemoryStream
* Initial Release

## Version v0.2.0.x (2018-07-24)

### ConvertFrom-CompressedByteArrayToString
* Initial Release

### ConvertFrom-MemoryStreamToString
* Added "System.IO.Stream" support
* Added the alias "ConvertFrom-StreamToString"

### ConvertFrom-StringToByteArray
* Initial Release

### ConvertFrom-StringToMemoryStream
* Added compression support

### ConvertTo-MemoryStream
* Added compression support

### ConvertTo-String
* Added "System.IO.Stream" support

## Version 0.1.1.x (2018-05-29)

### ConvertFrom-Base64ToString
* Added "-Decompress" support

### ConvertFrom-ByteArrayToBase64
* Initial Release

### ConvertFrom-CompressedByteArrayToString
* Initial Release

### ConvertFrom-StringToBase64
* Added "-Compress" support

### ConvertFrom-StringToCompressedByteArray
* Initial Release

### ConvertTo-Base64
* Added "-Compress" support

### ConvertTo-String
* Added "-Decompress" support

## Version 0.1.0.0 (2018-05-07)

### ConvertFrom-Base64ToString
* Initial Release

### ConvertFrom-Clixml
* Initial Release

### ConvertFrom-MemoryStreamToBase64
* Initial Release

### ConvertFrom-MemoryStreamToString
* Initial Release

### ConvertFrom-StringToBase64
* Initial Release

### ConvertFrom-StringToMemoryStream
* Initial Release

### ConvertTo-Base64
* Initial Release

### ConvertTo-Clixml
* Initial Release

### ConvertTo-MemoryStream
* Initial Release

### ConvertTo-String
* Initial Release
