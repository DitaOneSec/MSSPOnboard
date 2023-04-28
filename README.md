# Onboard Microsoft Sentinel Onesec MSSP

| Onesec Group         | Role | Delete the registration assignment assigned to their tenant (*) | Create and run Playbooks | Create automation Rules to run Playbooks | Can run Playbook Manually | Create and edit workbooks, analytic rules and other Azure Sentinel Resources | Manage incidents (dismiss, assign etc) | View data, incidents, dashboards and other Azure Sentinel resources |
|----------------------|------|----------------------------------------------------------------|--------------------------|------------------------------------------|--------------------------|--------------------------------------------------------------------|-------------------------------------|------------------------------------------------------------|
| MDR T1 - Analyst     | Microsoft Sentinel Reader + Microsoft Sentinel Playbook Operator | | X | | | | | X |
| MDR T2 - Analyst     | Microsoft Sentinel Responder + Microsoft Sentinel Automation Contributor | | X | | X | | | X |
| MDR T3 - Threat Hunter | Microsoft Sentinel Contributor + Logic App Contributor | X | X | X | X | X | X | X |



|Deployment Type | Button |
|----------------|--------|
| Subscription   | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsorcia25%2FMSSPOnboard%2Fmain%2FOnboard%2520Subscription%2FdelegatedResourceManagement.json) |
| Resource Group | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsorcia25%2FMSSPOnboard%2Fmain%2FOnboard%2520a%2520Resource%2520Group%2FrgDelegatedResourceManagement.json) |
