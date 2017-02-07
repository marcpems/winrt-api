---
-api-type: winrt property
---
 In the app manifest, specify the **Documents Library** capability. This capability is not visible in Manifest Designer. To add the Documents Library capability, open the app manifest in code view and edit the XML directly.
 In the app manifest, register at least one File Type Association declaration. This declaration explicitly indicates the file types (extensions) that your app wants to access in the Documents library. The app can only enumerate, create, or change files that have the file types declared in the app manifest. For more info, see [Handle file activation](http://msdn.microsoft.com/library/a0f914c5-62bc-4ff7-9236-e34c5277c363).