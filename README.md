# AWS-Account-Management-Solution
This solution provides a secure and compliant AWS infrastructure for XYZ Company, which includes the following objectives: 
• Divide the AWS infrastructure based on workload 
• Prevent developers from accidentally provision or utilize other regions that are not allowed in regulatory 
• Prevent the use of some AWS services in specific accounts 
• Track all API calls happening in all accounts 
• Reduce the creation of user accounts for developers in each sub AWS account 
• Protect the infrastructure from malware 
• Automate security checks across all AWS accounts 
• Track any resource changes

The solution leverages several AWS services and best practices, including: 
• AWS Control Tower 
• AWS Organizations 
• AWS SSO with Azure AD 
• AWS CloudTrail 
• AWS Service Control Policies 
• Amazon GuardDuty 
• AWS Config 
• AWS Security Hub

**Prerequisites**
To use this solution, you will need: • An AWS account with sufficient permissions to create and manage the required resources • An Azure AD account to use as an external identity provider with AWS SSO

**Usage**
To use this solution, follow these steps:
1.	Deploy AWS Control Tower in your AWS account.
2.	Create the necessary organization units (OUs) in AWS Organizations, based on the workload requirements of your company.
3.	Enable AWS SSO and use Azure AD as an external identity provider to manage access to AWS accounts.
4.	Enable AWS CloudTrail across all AWS Organization accounts, to track all API calls happening in all accounts.
5.	Create AWS Service Control Policies for each OU, to restrict the use of certain AWS services in specific accounts.
6.	Enable Amazon GuardDuty across all AWS Organization accounts, to detect and remediate potential security threats.
7.	Set up AWS Config to track any resource changes in the AWS infrastructure.
8.	Set up AWS Security Hub to automate security checks across all AWS Organization accounts.

**Contributing**
Contributions to this solution are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.

**License**
This solution is licensed under the MIT license. See the LICENSE file for more information.

**Disclaimer** 
This solution is provided as-is and may not be suitable for all use cases. Use at your own risk.


