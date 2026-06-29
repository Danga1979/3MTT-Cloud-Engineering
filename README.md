# 3MTT-Cloud-Engineering
This is for uploading my project and recording progress
# 3MTT Cloud Engineering Assignment

## Azure Free Tier Setup and Virtual Machine Deployment

### Student Information

* Name: Imbaji Danga
* Program: 3MTT Cloud Engineering
* Subscription: Azure for Students
* Resource Group: Imbaji_Cloud_Engine
* Virtual Machine: Cloud Engineering
* Region: France Central
* Operating System: Ubuntu Server 24.04 LTS

---

# Phase 1: Azure Account Setup

## Step 1: Create Azure for Students Account

I registered for the Azure for Students program using my Microsoft account. The Azure for Students subscription provides cloud resources for learning and experimentation without requiring a credit card.

### Screenshot 1: Azure Subscription Verification

**Description:** This screenshot shows the Azure Portal dashboard displaying the active Azure for Students subscription. It confirms that the subscription was successfully activated and is available for resource deployment.

---

## Step 2: Email Verification

During account registration, Microsoft sent a verification code to my email address. After entering the code, my email ownership was confirmed.

### Importance

Email verification protects the account and enables account recovery and service notifications.

---

## Step 3: Phone Verification

Microsoft also required phone number verification through an SMS code.

### Importance

Phone verification improves account security and helps prevent unauthorized access.

---

# Azure for Students Benefits and Limits

The Azure for Students subscription provides:

* Free Azure credits for learning purposes.
* Access to selected Azure services.
* No credit card requirement.
* Ability to create virtual machines, storage accounts, databases, and networking resources.
* Usage subject to service quotas and spending limits.

### Importance

Understanding subscription limits helps prevent resource deployment failures and unexpected charges.

---

# Phase 2: Azure Portal Navigation

After logging into Azure Portal, I explored the main dashboard and navigation menu.

## Services Accessed

* Resource Groups
* Virtual Machines
* Storage Accounts
* Cost Management + Billing
* Azure Monitor
* Networking

### Screenshot 2: Azure Portal Dashboard

**Description:** This screenshot displays the Azure Portal home page where services and resources can be accessed. The dashboard acts as the central management interface for Azure resources.

---

## Dashboard Customization

I customized the dashboard by pinning frequently used services.

Pinned Services:

* Resource Groups
* Virtual Machines
* Cost Management
* Azure Monitor

### Importance

Customizing the dashboard improves productivity by providing quick access to commonly used resources.

### Screenshot 3: Customized Dashboard

**Description:** This screenshot shows the customized dashboard with important Azure services pinned for easy access.

---

# Phase 3: Resource Group Creation

A Resource Group named **Imbaji_Cloud_Engine** was created.

## Purpose of Resource Groups

Resource Groups act as logical containers for organizing Azure resources.

Benefits include:

* Simplified administration
* Easier monitoring
* Centralized resource management
* Simplified resource deletion

### Screenshot 4: Resource Group Creation

**Description:** This screenshot confirms the successful creation of the Imbaji_Cloud_Engine Resource Group.

---

# Phase 4: Virtual Machine Deployment

A Linux Virtual Machine was deployed using the following configuration:

| Setting        | Value                   |
| -------------- | ----------------------- |
| VM Name        | Cloud Engineering       |
| Region         | France Central          |
| Image          | Ubuntu Server 24.04 LTS |
| Security Type  | Trusted Launch          |
| Authentication | SSH Public Key          |
| Username       | azureuser               |

### Screenshot 5: Virtual Machine Configuration

**Description:** This screenshot shows the VM deployment settings selected before resource creation.

---

# Phase 5: Billing and Cost Management

To monitor cloud spending, Azure Cost Management was accessed.

## Activities Performed

* Opened Cost Analysis
* Reviewed current spending
* Monitored resource consumption
* Explored budget creation options

### Screenshot 6: Cost Analysis

**Description:** This screenshot shows Azure Cost Analysis, which provides visibility into current and projected spending.

---

## Budget Alert Configuration

A budget alert was configured to notify users when spending reaches predefined thresholds.

Example thresholds:

* 50%
* 80%
* 100%

### Importance

Budget alerts help prevent overspending and promote responsible cloud resource usage.

### Screenshot 7: Budget Configuration

**Description:** This screenshot shows the Azure Budget configuration page used to create spending alerts.

---

# Phase 6: Security Configuration

Cloud security follows the Shared Responsibility Model.

## Microsoft Responsibilities

* Physical security
* Hardware maintenance
* Network infrastructure
* Platform availability

## Customer Responsibilities

* Identity management
* Access control
* Data protection
* Operating system security
* SSH key management

---

## Multi-Factor Authentication (MFA)

### How to Enable MFA

1. Open Microsoft Account Security Settings.
2. Select Advanced Security Options.
3. Enable Two-Step Verification.
4. Configure Microsoft Authenticator or SMS verification.
5. Complete verification process.

### Importance of MFA

Multi-Factor Authentication provides an additional layer of security beyond passwords. Even if a password is compromised, unauthorized users cannot access the account without the second authentication factor.

### Screenshot 8: Security Settings

**Description:** This screenshot shows account security settings and available authentication options.

---

# Phase 7: Shared Responsibility Model

For the deployed Ubuntu Virtual Machine:

### Azure Provides

* Physical datacenter security
* Infrastructure protection
* Network security
* Hypervisor management

### User Provides

* VM configuration
* User account security
* SSH key protection
* Software updates
* Application security

This model ensures both Azure and the customer contribute to maintaining a secure environment.

---

# Completion Checklist

## Azure Account Setup

* [x] Azure for Students account created
* [x] Email verified
* [x] Phone number verified
* [x] Azure Portal accessed

## Portal Navigation

* [x] Dashboard explored
* [x] Dashboard customized
* [x] Azure services reviewed

## Resource Management

* [x] Resource Group created
* [x] Virtual Machine deployed

## Billing and Cost Management

* [x] Cost Analysis accessed
* [x] Budget section reviewed
* [x] Cost monitoring completed

## Security

* [x] SSH authentication configured
* [x] Shared Responsibility Model documented
* [x] MFA process explained

## Documentation

* [x] Screenshots collected
* [x] Screenshot descriptions included
* [x] README completed
* [x] GitHub repository published

---

# Conclusion

This project successfully demonstrated the setup and use of Microsoft Azure through the Azure for Students subscription. Activities completed include account creation, portal navigation, dashboard customization, resource group creation, Linux virtual machine deployment, cost management review, security configuration, and documentation of the Shared Responsibility Model. The project provided hands-on experience with core cloud engineering concepts and Azure resource management.
