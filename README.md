# Password-Lockout-in-Azure AD
Set Authentication Password Policy Lockout threshold to 3 and duration to 250 seconds

<h2>Description</h2>
Lab consists of a create Password Lockout Policy by using Microsoft Azure AD.Smart lockout helps lock out bad actors that try to guess your users' passwords or use brute-force methods to get in. Smart lockout can recognize sign-ins that come from valid users and treat them differently than ones of attackers and other unknown sources. Attackers get locked out, while your users continue to access their accounts and be productive.	
<br />


<h2>Environments Used </h2>
- <b>Microsoft 365 Defender Portal </b>

<h2>Prerequisites</h2>

-<b> Password Lockout Settings modified by anyone assigned the following roles:
 - Security Administrator
 - Global Administrator
 </b>
- <b> Licenses:  Azure AD Premium P1 or higher licenses </b>

<h2>Program walk-through:</h2>

<h3>Steps: </h3>
1.  Go to Azure portal --> Azure AD --> Settings 
2.	In settings section --> go to Authentication methods
3.	Select Password Protection
4.	Enter value of Lockout threshold and Lockout duration in seconds
5.	Save 

<h3>Screenshots:</h3>

<p align="center">
Security:  <br/>
<img src="1.png" height="50%" width="50%" />
<br />
<br />
Authentication Methods:  <br/>
<img src="authentication methods.png" height="50%" width="50%" />
<br />
<br />
Lockout Settings: <br/>
<img src="lockout settings.png" height="50%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="result.png" height="65%" width="50%"/>
<br />
<br />
Testing: <br/>
<img src="test.png" height="65%" width="50%"/>
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
