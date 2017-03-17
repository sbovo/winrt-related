---
Description: Extensions (in Application) (Windows 10)
MS-HAID: UapManifestSchema.element\_1\_Extensions
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: Extensions (in Application) (Windows 10)
ms.assetid: 267051e3-b09c-467c-b5bd-4575cc31cb36
author: laurenhughes
ms.author: lahugh
keywords: windows 10, uwp, schema, package manifest
---

# Extensions (in Application) (Windows 10)


Defines one or more extensibility points for the app.

## Element hierarchy

<dl>
<dt><a href="element-package.md">&lt;Package&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-applications.md">&lt;Applications&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-application.md">&lt;Application&gt;</a></dt>
<dd><b>&lt;Extensions&gt;</b></dd>
</dl>
</dd>
</dl>
</dd>
</dl>

## Syntax

``` syntax
<Extensions>

  <!-- Child elements -->
  Extension{1,10000},
  uap:Extension{1,10000}

</Extensions>
```

### Key

`{}`   specific range of occurrences
## Attributes and Elements


### Attributes

None.

### Child Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Child Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[Extension (global)](element-1-extension.md)</td>
<td><p>Declares an extensibility point for the package.</p></td>
</tr>
<tr class="even">
<td>[uap:Extension](element-uap-extension.md)</td>
<td><p>Declares an extensibility point for the app.</p></td>
</tr>
</tbody>
</table>

 

### Parent Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parent Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[Application](element-application.md)</td>
<td><p>Represents an app that comprises part of or all of the functionality delivered in the package.</p></td>
</tr>
</tbody>
</table>

 

## Related elements


The following elements have the same name as this one, but different content or attributes:

-   **[Extensions (type: CT\_PackageExtensions)](element-extensions.md)**

## Remarks

Extensibility points are a mechanism by which an app can add functionality in a manner defined by the operating system. An example of an app extensibility point is the ability to create a file type association and enable your app to be the default handler for files with a specific file name extension.

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://schemas.microsoft.com/appx/manifest/foundation/windows10</p></td>
</tr>
</tbody>
</table>

 

 


