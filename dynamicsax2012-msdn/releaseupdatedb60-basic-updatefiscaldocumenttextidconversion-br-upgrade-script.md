﻿---
title: ReleaseUpdateDB60_Basic.updateFiscalDocumentTextIDConversion_BR Upgrade Script
TOCTitle: ReleaseUpdateDB60_Basic.updateFiscalDocumentTextIDConversion_BR Upgrade Script
ms:assetid: b76d1e84-bd8f-66dd-c413-0373f3a20d0b
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737056(v=AX.60)
ms:contentKeyID: 49710738
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Basic.updateFiscalDocumentTextIDConversion\_BR Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Basic</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateFiscalDocumentTextIDConversion_BR</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the text IDs from Microsoft Dynamics AX 2009 legal texts to Microsoft Dynamics AX 2012 fiscal document texts.</p></td>
</tr>
</tbody>
</table>


## Affected Modules and Tables

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Modules</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Basic</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Tables</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>BrazilParameters</p></td>
</tr>
<tr class="even">
<td><p>CFOPTable_BR</p></td>
</tr>
<tr class="odd">
<td><p>FiscalReferenceParm_BR</p></td>
</tr>
<tr class="even">
<td><p>FiscalDocumentReferenced_BR</p></td>
</tr>
<tr class="odd">
<td><p>FiscalDocument_BR</p></td>
</tr>
</tbody>
</table>


## Remarks

This method replaces the legacy Microsoft Dynamics AX 2009 text IDs with the new Microsoft Dynamics AX 2012 text IDs as they were defined in the pre-processing script. These new text IDs are necessary because the removal of the sales and purchase flag that may lead to duplicated text IDs.

  


