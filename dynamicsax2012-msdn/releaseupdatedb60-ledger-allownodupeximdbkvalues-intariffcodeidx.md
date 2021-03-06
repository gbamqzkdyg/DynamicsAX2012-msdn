﻿---
title: ReleaseUpdateDB60_Ledger.allowNoDupEximDBKValues_INTariffCodeIdx
TOCTitle: ReleaseUpdateDB60_Ledger.allowNoDupEximDBKValues_INTariffCodeIdx
ms:assetid: 81c9b678-5e78-133d-2ebd-7f04292f3969
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685934(v=AX.60)
ms:contentKeyID: 49709387
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowNoDupEximDBKValues\_INTariffCodeIdx 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupEximDBKValues_INTariffCodeIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the index &lt;c&gt;TariffCodeIdx&lt;/c&gt; in the table &lt;c&gt;EximDBKValues_IN&lt;/c&gt; not to allow duplicate records.</p></td>
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
<td><p>General ledger</p></td>
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
<td><p>EXIMDBKVALUES_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the surrogate key fields CustomsTariffCodeTable with the value of the RecId field of the tables, the index TariffCodeIdx is reset not to allow duplicate records.

  


