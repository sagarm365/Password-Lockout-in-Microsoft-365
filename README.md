# Password-Lockout-in-Azure AD
Set Authentication Password Policy Lockout threshold to 3 and duration to 250 seconds

<h2>Description</h2>
Lab consists of a create Safe Attachments Policy by using Microsoft Defender for Office 365. Safe Attachments protection for email messages is controlled by Safe Attachments policies.  Safe Attachments is a feature in Microsoft Defender for Office 365 that uses a virtual environment to check attachments in inbound email messages after they've been scanned by anti-malware protection. 
<br />


<h2>Environments Used </h2>
- <b>Microsoft 365 Defender Portal </b>

<h2>Prerequisites</h2>

-<b> Password Lockout Settings modified by anyone assigned the following roles:
 - Security Administrator
 - Global Administrator
 </b>
- <b> Licenses:  Azure AD Premium P1 or higher licenses for your users</b>

<h2>Program walk-through:</h2>

<h3>Steps: </h3>
1.  Go to Azure portal --> Azure AD --> Settings 
2.	In settings section --> go to Authentication methods
3.	Select Password Protection
4.	Enter value of Lockout threshold and Lockout duration in seconds
5.	Save 

<h3>Screenshots:</h3>

<p align="center">
Threat Policies:  <br/>
<img src="policies & rules.png" height="50%" width="50%" />
<br />
<br />
<img src="safe attachments.png" height="50%" width="50%" />
<br />
<br />
Give a Name : <br/>
<img src="create p.png" height="50%" width="50%"/>
<br />
<br />
Select 'HR' group: <br/>
<img src="include groups.png" height="65%" width="50%"/>
<br />
<br />
Policy Settings: <br/>
<img src="settings.png" height="65%" width="50%"/>
<br />
<br />
Review & Create: <br/>
<img src="review.png" height="65%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="result.png" height="65%" width="50%"/>
<br />
<br /> 

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
