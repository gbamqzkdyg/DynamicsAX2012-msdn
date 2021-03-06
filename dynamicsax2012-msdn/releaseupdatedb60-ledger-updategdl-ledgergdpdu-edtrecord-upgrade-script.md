﻿---
title: ReleaseUpdateDB60_Ledger.updateGDL_LedgerGDPdU_EDTRecord Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.updateGDL_LedgerGDPdU_EDTRecord Upgrade Script
ms:assetid: c021506d-31f7-f0f6-0ff6-0bad384a8781
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686768(v=AX.60)
ms:contentKeyID: 49710966
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.updateGDL\_LedgerGDPdU\_EDTRecord Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

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
<td><p>updateGDL_LedgerGDPdU_EDTRecord</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the surrogate key column in the foreign tables with the value from the RecId field of the primary table.</p></td>
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
<td><p>LedgerGDPdUField</p></td>
</tr>
<tr class="even">
<td><p>LedgerGDPdUGroup</p></td>
</tr>
<tr class="odd">
<td><p>LedgerGDPdURelation</p></td>
</tr>
<tr class="even">
<td><p>LedgerGDPdUTable</p></td>
</tr>
<tr class="odd">
<td><p>LedgerGDPdUTableSelection</p></td>
</tr>
</tbody>
</table>


## Remarks

Updates the LedgerGDPdUGroup field in the LedgerGDPdUTable table with the value from the RecId field of the LedgerGDPdUGroup table. Updates the LedgerGDPdUTable field in the LedgerGDPdUTableSelection, LedgerGDPdUField, and LedgerGDPdURelation tables with the value from the RecId field of the LedgerGDPdUTable table.

  


