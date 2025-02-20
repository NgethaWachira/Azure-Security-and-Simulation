# Objective
Steps for enhancing cloud security by assigning roles in Azure, automating resource onboarding with Microsoft Defender, testing user vulnerability 
to phishing through simulations, and setting up custom alerts for better threat detection.

## Skills Learned
- Importance of role assignment and access control in maintaining secure access to cloud resources. Understanding IAM (Identity and Access Management) 
and managing subscriptions effectively for protecting the environment.

- Automating the onboarding of Azure resources, such as turning on endpoint protection in Defender for Cloud, streamlines security processes 
and ensures resources are protected from the start.

- Testing users through simulated phishing attacks helps identify vulnerabilities, while targeted training ensures they can recognize and avoid future 
threats, strengthening overall cybersecurity awareness

- Setting up custom alert policies in Microsoft Defender allows tailored monitoring, enabling faster identification and response to potential threats.

- Customizing email addresses and using user-friendly domains in Microsoft 365 helps establish professionalism and trust, while also enabling greater 
flexibility in managing accounts.

## Tools Used
<div>
<img src="https://img.shields.io/badge/-Azure-00ffff?style=for-the-badge&logo=Microsoft%20Azure&logoColor=white" alt="Azure">
<img src="https://img.shields.io/badge/-Microsoft%20Defender%20for%20Cloud-404040?style=for-the-badge&logo=Microsoft%20Azure&logoColor=white" alt="Microsoft Defender for Cloud">
<img src="https://img.shields.io/badge/-Microsoft%20Defender-ffbb33?style=for-the-badge&logo=Microsoft%20Defender&logoColor=white" alt="Microsoft Defender">
<img src="https://img.shields.io/badge/-Microsoft%20Defender%20for%20Office%20365-cc0044?style=for-the-badge&logo=Microsoft%20Office%20365&logoColor=white" alt="Microsoft Defender for Office 365">
<img src="https://img.shields.io/badge/-Microsoft%20365%20Admin%20Center-ff33ff?style=for-the-badge&logo=Microsoft%20365&logoColor=white" alt="Microsoft 365 Admin Center">
</div>

## Steps
- Log in to Azure portal and navigate to all services to open the full list of available Azure services. Search and select Subscriptions from the list. Click on the subscription you want to assign roles to. Once you're inside your selected subscription, find and click on "Access Control (IAM)". This section is where you can
manage role assignments and permissions. Add role assignment and a new window will pop up. You can search for the role you want. We can assign the role to a User, Group, Service Principal, or Managed Identity. After assiggnment, the user will now have the permissions associated with the role you've assigned to them.

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/50030693511ae30bd53520e104dde01e51351ce0/Images/Subscription%20role%20assignment.PNG" width="700" />
</p>

- From the All Services Tab and search for and click on Defender for Cloud. Scroll down to the Management section and click on Environmental Settings. Within Environmental Settings, you'll see an option for Defender Plans Coverage. Click on it to view the available plans. Under Subscription Name, you'll see a list of your subscriptions. Find and select the subscription where you want to enable automatic onboarding.

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/eaffac99aee848222a7efbc1b4776976a1fe27bb/Images/Automating%20onboardin%20gof%20azure%20resources.PNG" width="300" />
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/eaffac99aee848222a7efbc1b4776976a1fe27bb/Images/Subscription%20plan%20for%20servers.PNG" width="300" />
</p>

- Make sure that the Servers plan is selected for the subscription you're working with. Under Servers, ensure that the status is set to On. If it’s not, click on it to enable it. Under the Monitoring Coverage section, locate Servers and click on Settings within that section. In the Settings window, confirm that Endpoint Protection is turned on. This is essential for the automatic onboarding of Azure resources and Endpoint Protection will be active to protect our resources.

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/2abacbf56104bc162ba164c5672f8049e0aa57de/Images/Monitoring%20coverage%20turn%20on%20under%20settings.PNG" width="300" />
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/2abacbf56104bc162ba164c5672f8049e0aa57de/Images/We%20confirm%20that%20automatic%20onboarding%20for%20azure%20is%20enabled.PNG" width="300" />
</p>

- Next we Log in to the Microsoft Defender Portal, navigate to Email & Collaboration under the Microsoft Defender section and click on Attack simulation training. You will need either Microsoft Defender for Office 365 Plan 2, or Microsoft 365 E5 to run an attack simulation, which for our case we have Microsoft 365 E5. Once you confirm you have the right license, go to Email & Collaboration and click the Attack Simulator option. We can now configure and run attack simulations, such as phishing, credential harvest, or other attack types. Follow the prompts to set up and configure the simulation.

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/670ae5d5cd00a045199063fcee2303e6b30fae0e/Images/Launching%20an%20attack%20simulation.PNG" width="300" />
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/8d2d52d3bc3c8de99ab8e47cacda47b5ec8010f3/Images/Attack%20email%20payload.PNG" width="300" />
</p>

- After the simulation runs, review the results to assess how well users in your organization are prepared to detect and respond to phishing or other social engineering attacks. Use the results to improve your organization's security training and awareness programs. Assign training to users who fall for the attack to help improve their awareness and response.

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/8d2d52d3bc3c8de99ab8e47cacda47b5ec8010f3/Images/Simulation%20report.PNG" width="700" />
</p>

- Next, we set up Custom Alert Detections in Microsoft Defender by loging in to Microsoft defender portal, under Microsoft Defender, click on Email & Collaboration, scroll down to find Policies & Rules. Click on Alert Policy, here you can manage and create alert policies. 

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/ef0a4b00b32f1abfb1d90545637bce8aaffaf192/Images/Creating%20custom%20alert%20detections.PNG" width="700" />
</p>

- Click on New Alert Policy to start creating a custom policy and provide the necessary details for the alert policy, such as the name, description, and the conditions for triggering the alert. We select the conditions and events that we want to trigger the alert, such as suspicious email activity or specific patterns in emails. We review our settings and save the new alert policy.

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/5d509782cd251223474292401d6715d180b5f71c/Images/Creating%20new%20alert%20policy.PNG" width="300" />
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/5d509782cd251223474292401d6715d180b5f71c/Images/New%20alert%20policy%20is%20created.PNG" width="300" />
</p>

- Once the custom alert policy is active, alerts will trigger based on the conditions we've set. To view the alerts, we go to the Investigation & Response section in Microsoft Defender. Click on Alerts to view all the triggered alerts and take the necessary actions. 

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/570665c8c9f88fffcf25dda1c4f91a8c2e657387/Images/Displaying%20triggered%20alerts.PNG" width="700" />
</p>


