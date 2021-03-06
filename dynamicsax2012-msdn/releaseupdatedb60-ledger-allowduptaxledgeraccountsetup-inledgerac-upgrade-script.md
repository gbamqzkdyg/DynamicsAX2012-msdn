﻿---
title: ReleaseUpdateDB60_Ledger.allowDupTaxLedgerAccountSetup_INLedgerAc Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupTaxLedgerAccountSetup_INLedgerAc Upgrade Script
ms:assetid: a7a7118a-8e2f-9fce-33de-5c0a4485c6ca
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686370(v=AX.60)
ms:contentKeyID: 49710326
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupTaxLedgerAccountSetup\_INLedgerAc Upgrade Script 


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
<td><p>allowDupTaxLedgerAccountSetup_INLedgerAc</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the GroupCodeNumIdx index in the TaxLedgerAccountSetup_IN table to allow duplicate records.</p></td>
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
<td><p>TAXLEDGERACCOUNTSETUP_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

The TaxAccountGroup and RegistrationNumber fields are replaced with the new TaxLedgerAccountGroup and TaxRegistrationNumberTable surrogate key fields in the unique GroupCodeNumIdx index. Initially these fields contain no value. So the index is set to allow duplicates before the field is updated with the value of the RecId fields of the TaxLedgerAccountGroup\_IN and TaxRegistrationNumberTable\_IN tables.

  


