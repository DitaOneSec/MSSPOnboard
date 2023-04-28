# Onboard Microsoft Sentinel Onesec MSSP

<table>
<thead>
<tr>
  <th>Onesec Group</th>
  <th>Role</th>
  <th>Delete the registration assignment assigned to their tenant (*)</th>
  <th>Create and run Playbooks</th>
  <th>Create automation Rules to run Playbooks</th>
  <th>Can run Playbook Manually</th>
  <th>Create and edit workbooks, analytic rules and other Azure Sentinel Resources</th>
  <th>Manage incidents (dismiss, assign etc)</th>
  <th>View data, incidents, dashboards and other Azure Sentinel resources</th>
</tr>
</thead>
<tbody>
<tr>
  <td>MDR&nbsp;T1&nbsp;-&nbsp;Analyst</td>
  <td>Microsoft&nbsp;Sentinel&nbsp;Reader&nbsp;+&nbsp;Microsoft&nbsp;Sentinel&nbsp;Playbook&nbsp;Operator</td>
  <td></td>
  <td style="text-align:center">X</td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td style="text-align:center">X</td>
</tr>
<tr>
  <td>MDR&nbsp;T2&nbsp;-&nbsp;Analyst</td>
  <td>Microsoft&nbsp;Sentinel&nbsp;Responder&nbsp;+&nbsp;Microsoft&nbsp;Sentinel&nbsp;Automation&nbsp;Contributor</td>
  <td></td>
  <td<center>X</center></td>
  <td></td>
  <td style="text-align:center">X</td>
  <td></td>
  <td></td>
  <td style="text-align:center">X</td>
</tr>
<tr>
  <td>MDR&nbsp;T3&nbsp;-&nbsp;Threat&nbsp;Hunter</td>
  <td>Microsoft&nbsp;Sentinel&nbsp;Contributor&nbsp;+&nbsp;Logic&nbsp;App&nbsp;Contributor</td>
  <td<center>X</center></td>
  <td style="text-align:center">X</td>
  <td style="text-align:center">X</td>
  <td style="text-align:center">X</td>
  <td style="text-align:center">X</td>
  <td style="text-align:center">X</td>
  <td style="text-align:center">X</td>
</tr>
</tbody>
</table>



|Deployment Type | Button |
|----------------|--------|
| Subscription   | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsorcia25%2FMSSPOnboard%2Fmain%2FOnboard%2520Subscription%2FdelegatedResourceManagement.json) |
| Resource Group | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsorcia25%2FMSSPOnboard%2Fmain%2FOnboard%2520a%2520Resource%2520Group%2FrgDelegatedResourceManagement.json) |
