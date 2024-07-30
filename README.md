# Onboard Automator

Automate the process of onboarding a new employee into Azure AD and assigning necessary Azure resources without requiring programming.

## Features
- Automated user creation in Azure AD
- Role and group assignment
- Azure resource provisioning
- Welcome email notification
- Monitoring and review of the onboarding process

## Prerequisites
- Azure subscription
- Basic knowledge of Azure AD and Logic Apps

## Setup Guide

### Step 1: Azure AD Setup
Follow the instructions in [Azure AD Setup Guide](azure_ad_setup_guide.md).

### Step 2: Logic App Workflow Design
Import the [Logic App Workflow](https://github.com/RichardChukwu/OnboardAutomator/blob/main/Logic%20App%20Workflow.png) into your Azure Logic Apps designer.

### Step 3: Configuration
- Configure triggers and actions as per your requirements.
- Ensure all connectors are authenticated.

### Monitoring and Review
- Check Logic Apps run history for workflow executions.
- Review Azure AD audit logs for user creation and modifications.

## Documentation
Detailed documentation is available [here](docs/Onboard_Automator_Documentation.md).

## Contribution
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
