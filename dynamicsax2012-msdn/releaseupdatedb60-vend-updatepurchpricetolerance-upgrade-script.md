﻿---
title: ReleaseUpdateDB60_Vend.updatePurchPriceTolerance Upgrade Script
TOCTitle: ReleaseUpdateDB60_Vend.updatePurchPriceTolerance Upgrade Script
ms:assetid: 0701b683-5123-3b7e-19e3-ca12f4407b0a
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ684744(v=AX.60)
ms:contentKeyID: 49706440
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Vend.updatePurchPriceTolerance Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Vend</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updatePurchPriceTolerance</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the value of the ItemRelation and AccountRelation fields to empty values instead of &quot;*&quot;.</p></td>
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
<td><p>Accounts payable</p></td>
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
<td><p>PurchPriceTolerance</p></td>
</tr>
</tbody>
</table>


## Remarks

In prior releases, a value of "\*" in the ItemRelation or AccountRelation fields in the PurchPriceTolerance table indicated that a range that was not set. This was changed in Microsoft Dynamics AX 2012 and now an empty value indicates that a range is not set.

  


