# Enable-Multi-Factor-Authentication-MFA-on-AWS-Root-Account-User
#### Secure your AWS Management Console with Multi-Factor Authentication (MFA). This repository provides clear instructions and scripts for enabling MFA on the Root Account User, enhancing access security and compliance within your AWS environment.
<img src= "https://github.com/glory-violet/Enable-Multi-Factor-Authentication-MFA-on-Root-Account-User/assets/137056419/fa610d8e-abdf-4e18-9cc9-80c631735dea" width="800" height="250">
<img src= "https://github.com/glory-violet/Enable-Multi-Factor-Authentication-MFA-on-AWS-Root-Account-User/assets/137056419/0b840ac5-264c-412f-93fd-21cee76df7d0" width="800" height="250">
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Scenario - "WHAT" Challenges the Need for Multi Factor Authentication (MFA) on the Root Account user?
#### For medium-sized tech company that relies heavily on AWS for its infrastructure and services. The root account in AWS serves as the highest level of access and control over the company's AWS resources. It is typically used for administrative tasks such as...
  1. Managing Billing
  2. Creating IAM Users
  3. Configuring Global Settings

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Problem Statement - "WHY" to Enable Multi Factor Authentication (MFA) on the root account user?
#### Without Multi-Factor Authentication (MFA) enabled, the root account is protected only by a password. In this scenario, if a malicious actor gains access to the root account credentials through methods like phishing attacks or brute force attempts, they could potentially wreak havoc on the company's AWS environment. They could delete critical resources, steal sensitive data, or even incur substantial financial losses by spinning up expensive services.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Solution - "HOW" does Multi-Factor Authentication (MFA) Enhance Security for the Root Account User?
#### With MFA enabled, even if an attacker somehow obtains the root account password, they would still need access to the physical MFA device (such as a smartphone or hardware token) to complete the login process.

## Implementation Steps:
### Step - 1: Log in to the AWS Management Console with root User credentials.
- Click on the drop down menu beside the profile name, to the top right hand side.
- Select "Security Credentials" option.
<img src= "https://github.com/glory-violet/Enable-Multi-Factor-Authentication-MFA-on-Root-Account-User/assets/137056419/47b20051-f3d2-477e-a2f5-93f98354e334" width="450" height="300">

### Step - 2: My Security Credentials - Enabling Multi-Factor Authentication (MFA):
- Scroll down to the "Multi-factor authentication (MFA)" section.
- Click on "Assign MFA Device"
- Define a "Device Name" (It will reflect in the Authenticator Device you will be using on your mobile, such as Google Authenticator or Authy.)
- Select the "MFA Device" type as "Authenticator App
- Click on "Next"
- You will be redirected to "Setup Device" screen. (Here we need to configure the Authenticator App)
- Scroll down and click on "Show QR Code", in order to scan the code we need to install an Authenticator App.
<img src= "https://github.com/glory-violet/Enable-Multi-Factor-Authentication-MFA-on-Root-Account-User/assets/137056419/015d0582-3606-4b66-a995-939c4e79bdef" width="450" height="300">

### Step - 3: Install Google Authenticator
- Navigate to "Play Store" in your mobile.
- Type "Google Authenticator" and install the App
<img src= "https://github.com/glory-violet/Enable-Multi-Factor-Authentication-MFA-on-Root-Account-User/assets/137056419/b91e0535-3467-4ef7-84c4-3271532f6ec5" width="500" height="300"> 


- Once installed, open "Google Authenticator App"
- Press the plus "+" icon
- It give you 2 options
  1. Scan a QR Code
  2. Enter a setup key
- Select "Scan the QR Code" to scan the code displayed on the AWS Management Console


- Once the MFA device is set up, confirm the setup by entering the generated MFA code.

**MFA Code 1**  
| 123456 |
| ------ |

**MFA Code 2**
| 654321 |
| ------ |

- Click on "Add MFA"

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## How to sign in using MFA
#### 1. Log in with your username and password.
#### 2. Your computer shows a two-digit number, and a notification is sent to your phone.
#### 3. Open the authenticator app, enter the number on your computer screen















------------------------------------------------------------- **THANK YOU** ---------------------------------------------

