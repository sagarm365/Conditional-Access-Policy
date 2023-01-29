# Conditional-Access-Policy
Set conditional  access to block high risk users using Android for Cloud Apps.

<h2>Description</h2>
Project consists of a creating a Conditional Access Policiy to block High risk users.Conditional Access deployment is critical to achieving your organization's access strategy for apps and resources. Conditional Access is setting up a policy to manage access to Microsoft Azure Management In this practical, it is auto applying for high risk users using Android for Cloud Apps.
<br />


<h2>Environments Used </h2>

- <b>Microsoft Azure Portal</b> 
- <b>Azure Active Directory service</b>

<h2>Prerequisites</h2>

-<b> Conditional Access Policy can be created or modified by anyone assigned the following roles:
 - Conditional Access Administrator
 - Security Administrator
 - Global Administrator
 </b>
- <b> Licenses: Azure AD Premium or trial license</b>


<h2>Program walk-through:</h2>

<h3>Steps: </h3>

1.  Azure portal  --> Azure AD --> Security --> Conditional Access
2.	+new policy --> give name, select users, cloud apps
3.	Conditions --> select User risk & sign-in risk ‘high’
4.	Device platforms --> select ‘Android’
5.	Block access and Enable policy on
6.	create




<h3>Screenshots:</h3>

<p align="center">
Create new CA policy: <br/>
<img src="new policy.png" height="50%" width="50%" />
<br />
<br />
Conditions set: <br/>
<img src="sign-in risk.png" height="50%" width="50%"/>
<br />
<br />
Device select: <br/>
<img src="device platforms.png" height="65%" width="50%"/>
<br />
<br />
Block access and Enable policy on: <br/>
<img src="block access & enable policy.png" height="65%" width="50%"/>
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
