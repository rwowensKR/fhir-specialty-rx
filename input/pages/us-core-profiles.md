### US Core Profiles Used With This Guide

The [Search Conventions](searches.html) section outlines required and recommended searches performed in this guide's query workflows. These searches conform to US Core search parameter requirements and SHALL return resources that conform to US Core resource profiles.

<table class="grid" style="width:100%">
<colgroup>
  <col width="300">
  <col>
</colgroup>
<thead>
<tr>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://www.hl7.org/fhir/us/core/StructureDefinition-us-core-allergyintolerance.html">US Core AllergyIntolerance</a></td>
<td>This profile sets minimum expectations for AllergyIntolerance resources returned in this guide's query workflows.</td>
</tr>
<tr>
<td><a href="http://hl7.org/fhir/us/core/StructureDefinition-us-core-condition.html">US Core Condition</a></td>
<td>This profile sets minimum expectations for Condition resources returned in this guide's query workflows</td>
<tr>
<td><a href="http://hl7.org/fhir/us/core/StructureDefinition-us-core-documentreference.html">US Core Document Reference</a></td>
<td>This profile sets minimum expectations for DocumentReference resources returned in this guide's query workflows.</td>
</tr>
<tr>
<tr>
<td><a href="https://www.hl7.org/fhir/us/core/StructureDefinition-us-core-observation-lab.html">US Core Laboratory Result Observation</a></td>
<td>This profile sets minimum expectations for Observation resources returned in this guide's query workflows.</td>
</tr>
<tr>
</tr>
<td><a href="https://www.hl7.org/fhir/us/core/StructureDefinition-us-core-medicationrequest.html">US Core Medication Request</a></td>
<td>This profile sets minimum expectations for MedicationRequest resources returned in this guide's query workflows.</td>
</tr>
</tbody>
</table>

Further, when other resources not profiled in this implementation guide are exchanged as part of a Specialty Rx workflow (for example, other resource types returned in response to a Specialty Rx Query message), they SHOULD conform to US Core profiles where applicable profiles exist.

*See [full list of US Core profiles](https://www.hl7.org/fhir/us/core/profiles.html)*

<br>

