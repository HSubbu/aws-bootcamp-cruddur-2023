
**INITIAL PREPARATION**

Rgistered for registered the following services:

* Github Account. - already had an A/c
* Create a Gitpod account and install the extension for your browser(chrome)
* Create Github CodeSpace.
* Create the AWS account - Using existing rot a/c but created a IAM user 
* Create Lucidchart. This app allows you to create chart/diagrams. 
* honeycomb.io account
* Create Rollbar account.




**ARCHITECTURE DIAGRAM**

https://lucid.app/lucidchart/0f5860ce-2327-4b39-8aaf-16e5282269f5/edit?invitationId=inv_12a7a84e-1c67-4ed7-928c-a519db19a6af

<img width="798" alt="image" src="https://user-images.githubusercontent.com/30765337/219711559-c3e70ff7-0e80-4ee1-8f51-a9924b347820.png">


**SET MFA & IAM ROLES**

(a) I have created MFA for root user and IAM (AWS admin permissons) and I am using *Microsoft Authenticator* as second authentication . Some screen shots attached. 

![image](https://user-images.githubusercontent.com/30765337/219723479-78d782ee-39d1-4637-8bf0-ead3fe73ca3d.png)

![image](https://user-images.githubusercontent.com/30765337/219723820-48578f0a-907c-4183-bd89-2986775ccf7c.png)

<img width="736" alt="image" src="https://user-images.githubusercontent.com/30765337/219724856-cef35bac-9ab4-4d6a-b75b-9b0261f9e2ca.png">

**CLOUD SHELL**

AWS CloudShell is a browser-based shell that makes it easier to securely manage, explore, and interact with your AWS resources. CloudShell is pre-authenticated with your console credentials.
<img width="881" alt="image" src="https://user-images.githubusercontent.com/30765337/219733057-d971b605-e4e3-49f3-82e6-a68f45b0f7fc.png">

**BILLING ALERTS**

There are 2 ways to set the billing alerts.It can be set through GUI or AWS CLI.

* Budget.
* Cloudwatch Alarm.

<img width="1170" alt="image" src="https://user-images.githubusercontent.com/30765337/219799199-26d5fff3-4704-4c49-a3b1-5d4cfcd0a1f6.png">

<img width="569" alt="image" src="https://user-images.githubusercontent.com/30765337/219799284-e988cfcb-5377-41b2-80d5-47fd99fee822.png">

One alarm to notify a warning when estimated charges > $10 has been created through GUI and notification for the same has reached by email. This was created through GUI. 

<img width="1093" alt="image" src="https://user-images.githubusercontent.com/30765337/219799600-908097e0-92b5-499c-a480-9dc75e9f4fda.png">

similerly , a budget limit has been created through Billing>budget on AWS console. 

**CREATING A BUDGET THROUGH AWS CLI**




