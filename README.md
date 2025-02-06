# Azure-AD-Security-Access-Management-Part-4-Monitoring-Reporting-and-Incident-Response
Azure AD - Monitoring, Reporting, and Incident Response

## Step 1: Set Up Monitoring and Alerts
### Enabling Azure AD Diagnostic Logs to forward the Audit and Sign-in logs to a Log Analytics Workspace.
- Create a Log Analytics Workspace.
   
![Screenshot 2025-02-05 140339](https://github.com/user-attachments/assets/17a8c064-5af7-4b14-a5a8-d7eeeb61192d)

- Azure AD > Diagnostic settings > Add diagnostic setting.

![Screenshot 2025-02-05 140108](https://github.com/user-attachments/assets/9a4939e5-0e63-4509-b929-e949aa8a0995)

   <br><br>

![Screenshot 2025-02-05 140751](https://github.com/user-attachments/assets/7d0c14a6-9690-42a8-a533-63df7a3923fd)


### Configuring Alerts for Suspicious Activities.
- Go to Monitor > Alerts > Create > Alert Rules

![Screenshot 2025-02-05 164107](https://github.com/user-attachments/assets/5acc42cb-cd57-4d83-9982-bfd98124d980)

- Add the resource that we want to track and be alerted to if there are any suspicious activities going on. In this case, I will add the LogAnalytics Workspace as the resource since all the logs are being sent to it(a centralized space).

![Screenshot 2025-02-05 164325](https://github.com/user-attachments/assets/4073747d-efac-4a62-a3d8-be6f61a67d43)

<br><br>

![Screenshot 2025-02-05 165014](https://github.com/user-attachments/assets/84e27f49-e615-4fba-b5d5-963f981f2089)

<br><br>

