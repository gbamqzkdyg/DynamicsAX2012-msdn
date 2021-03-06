﻿---
title: ReleaseUpdateDB60_Invent.allowDupTaxInventVATCommodityCode_INItem
TOCTitle: ReleaseUpdateDB60_Invent.allowDupTaxInventVATCommodityCode_INItem
ms:assetid: e9ceb136-7a36-9820-8d66-2e2a334c743b
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719874(v=AX.60)
ms:contentKeyID: 49711947
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Invent.allowDupTaxInventVATCommodityCode\_INItem 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Invent</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowDupTaxInventVATCommodityCode_INItem</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the index &lt;c&gt;ItemLogisticAddressStateIdx&lt;/c&gt; in the table &lt;c&gt;TaxInventVATCommodityCode_IN&lt;/c&gt; to allow duplicate records.</p></td>
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
<td><p>Inventory management</p></td>
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
<td><p>TAXINVENTVATCOMMODITYCODE_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

The StateId field is replaced with the new global address field LogisticsAddressStateId in the unique ItemLogisticAddressStateIdx. Initially this field contains no value. So the index is set to allow duplicates before the field is updated with the value of the RecId field of the table TaxInventVATCommodityCode\_IN.

  


