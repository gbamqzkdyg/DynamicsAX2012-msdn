﻿---
title: ReleaseUpdateDB60_smm.updatesmmCampaignSelectionWorker Upgrade Script
TOCTitle: ReleaseUpdateDB60_smm.updatesmmCampaignSelectionWorker Upgrade Script
ms:assetid: 4cf3f76e-b64f-3148-e6e1-09de638c86db
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685425(v=AX.60)
ms:contentKeyID: 49708130
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_smm.updatesmmCampaignSelectionWorker Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_smm</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updatesmmCampaignSelectionWorker</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Migrates data from the DEL_ResponsibleEmpFollowUp field to the FollowUpRespWorker field and the DEL_BusRelMainResponsible field to the BusRelMainRespWorker field in the smmCampaignSelection table.</p></td>
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
<td><p>CRM</p></td>
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
<td><p>smmCampaignSelection</p></td>
</tr>
</tbody>
</table>


## Remarks

The HCMWorker table and associated tables have replaced the Employee table, that is the EmplTable table, and associated tables in Microsoft Dynamics AX 2012. This transition requires an upgrade.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: smmCampaignSelection</p></th>
<th><p>To Table: smmCampaignSelection</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>DEL_ResponsibleEmpFollowUp</p></td>
<td><p>FollowUpRespWorker</p></td>
</tr>
<tr class="even">
<td><p>DEL_BusRelMainResponsible</p></td>
<td><p>BusRelMainRespWorker</p></td>
</tr>
</tbody>
</table>


## New Tables or Fields

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
<th><p>Extended Data Type</p>
<p>-or- Base Enum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>smmCampaignSelection</p></td>
<td><p>FollowUpRespWorker</p></td>
<td><p>CrmWorkerRecId</p></td>
</tr>
<tr class="even">
<td><p>smmCampaignSelection</p></td>
<td><p>BusRelMainRespWorker</p></td>
<td><p>CrmWorkerRecId</p></td>
</tr>
</tbody>
</table>


## Deleted Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>smmCampaignSelection</p></td>
<td><p>DEL_ResponsibleEmpFollowUp</p></td>
</tr>
<tr class="even">
<td><p>smmCampaignSelection</p></td>
<td><p>DEL_BusRelMainResponsible</p></td>
</tr>
</tbody>
</table>

  


