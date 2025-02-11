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
<img src="https://img.shields.io/badge/-Microsoft%20Defender%20for%20Cloud-ffff00?style=for-the-badge&logo=Microsoft%20365&logoColor=white" alt="Microsoft Defender for Cloud">
<img src="https://img.shields.io/badge/-Microsoft%20365%20Defender-e600ac?style=for-the-badge&logo=Microsoft%20Office&logoColor=white" alt="Microsoft 365 Defender">
</div>

## Steps
- Log in to Azure portal and navigate to all services to open the full list of available Azure services. Search and select Subscriptions from the list. Click on the subscription you want to assign roles to. Once you're inside your selected subscription, find and click on "Access Control (IAM)". This section is where you can
manage role assignments and permissions. Add role assignment and a new window will pop up. You can search for the role you want. We can assign the role to a User, Group, Service Principal, or Managed Identity. After assiggnment, the user will now have the permissions associated with the role you've assigned to them.

<p align="center">
  <img src="https://github.com/NgethaWachira/Azure-Security-and-Simulation/blob/50030693511ae30bd53520e104dde01e51351ce0/Images/Subscription%20role%20assignment.PNG" width="700" />
</p>

From the All Services Tab and search for and clock on Defender for Cloud. Scroll down to the Management section and click on Environmental Settings. Within Environmental Settings, you'll see an option for Defender Plans Coverage. Click on it to view the available plans. 
