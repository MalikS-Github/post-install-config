<p align="center">
<img src="https://static.wixstatic.com/shapes/2ebf04_6ddec2f2c2eb4cd4ada9cef3f6ace924.svg" alt="osTicket Logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial provides a comprehensive guide to the post-installation configuration procedures of the open-source help desk ticketing system, osTicket. Users can learn how to optimize their osTicket installation by configuring its various admin/agent settings, including roles, departments, ticket templates, and more.<br />


</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Establish a senior administrator position with appropriate role-based access control privileges and permissions.
- Implement a new department for system administrators.
- Configure one team responsible for level II support issues.
- Create three agents with distinct roles and permissions based on their job requirements.
- Add two users who will serve as example customers by sending in support tickets.
- Configure service-level agreements (SLAs) by establishing performance metrics and customer service targets.
- Set up four help topics that enable customers to easily narrow down their support issues.

<p>
<p align="center"> 
<h2>Configuration Steps</h2>
<img width="773" alt="Step 1 " src="https://github.com/MalikS-Github/post-install-config/assets/173410266/4a4c63f8-0a0f-4eb4-97b6-bf31af6cac46">
<br />

<p>
<p align="center"> 
<img width="775" alt="Step 2" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/2292b382-cf8a-492f-a39b-d7dde6a5f9ba">
</p>
<p align="center"> 
<img width="773" alt="Step 3" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/f65c798e-b2f7-496f-a87e-07b4beafddaa">
</p>
<p align="center"> 
</p>
<p align="center"> 
<img width="770" alt="Step 4" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/1fb5580c-1d42-4fa6-a489-4be8f09bb4d8">
</p>
<p>
Step 1: Navigate to the admin panel, then click on Agents, followed by Roles, and select the option to add new roles.
</p>
<br />
<p>
<p align="center"> 
<img width="767" alt="Step 5" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/631ad6ee-0519-4f03-9b07-7d0789d42554">
</p>
<p>
Step 2: Name the new role as "Supreme Admin."
</p>
<br />
<p>
<p align="center"> 
<img width="773" alt="Step 6" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/758275a7-450c-4c9e-bb0b-ae26f516778c">
</p>
<p>
Step 3: Choose all the permissions for the Senior Administrator role in the Tickets, Tasks, and Knowledgebase tabs, and click "Add Role."
</p>
<br />

<p>
<p align="center"> 
<img width="772" alt="Step 7" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/4e7072e9-a4dd-4523-9548-49073608067b">
</p>
<p align="center"> 
<img width="769" alt="Step 9 " src="https://github.com/MalikS-Github/post-install-config/assets/173410266/1e350a50-6245-49c3-a95c-7920f7eade4a">
</p>
<p>
Step 4: Navigate to Departments and select the option to add a new department.
</p>
<br />

<p>
<p align="center"> 
<img width="771" alt="Step 10" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/8622abda-93f6-455a-ae28-0b81bbf95b0e">
</p>
<p align="center"> 
<img width="776" alt="Step 10-2" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/cb85f155-5418-4750-911c-29e7541ed521">
</p>
<p>
Step 5: Name the department as "System Administrators" and click on "Create Dept."
</p>
<br />

<p>
<p align="center"> 
<img width="773" alt="Step 11" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/604116cb-47ea-470e-8ebc-45b6191f0165">
</p>
<p align="center"> 
<img width="773" alt="Step 12" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/9e6285c9-cb30-4fd5-b543-16ec5f85e2ea">
</p>
<p>
Step 6: Go to Teams and select the option to add a new team.
</p>
<br />

<p>
<p align="center"> 
<img width="773" alt="Step 13" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/6164fe7e-ca5b-41a2-8bd9-4042d18f3c08">
</p>
<p align="center"> 
<img width="768" alt="Step 13-2" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/42d85771-d258-4072-b2de-649a3a54b98d">
</p>
<p>
Step 7: Name the team "Level II Support," add yourself as a team member, and click on "Create Team."
</p>
<br />

<p>
<p align="center"> 
<img width="773" alt="Step 14" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/a60bab62-6db1-4c00-8ade-ceeba28e047f">
</p>
<p align="center"> 
<img width="775" alt="Step 15" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/5300822e-27ca-46fa-9eb0-4f9dd4483fa9">
</p>
<p>
Step 8: Go to Agents and select the option to add new agents.
</p>
<br />

<p>
<p align="center"> 
<img width="649" alt="Step 19" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/b9be4685-f4eb-43ad-be9f-73b7c2c35b60">
</p>
<p>
Step 9: Fill out the text input fields under "Account" to add three new agents.
</p>
<br />

<p>
<p align="center"> 
<img width="435" alt="Step 20" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/d192ff4d-f015-4c93-b968-a361821d0ecf">
</p>
<p>
Step 10: Click on "Set Password," then uncheck the option "Send the agent a password reset email."
</p>
<br />

<p>
<p align="center"> 
<img width="435" alt="Step 20-2" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/53da8279-965c-4423-94de-6e1c6d55257d">
</p>
<p>
Step 11: Enter a password and click on "Set."
</p>
<br />

<p>
<p align="center"> 
<img width="652" alt="Step 21" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/8e039fa7-f762-4ec1-b5ec-364d7ddfc9be">
</p>
<p>
Step 12: For Agent 1, under the "Access" tab, assign them to the System Administrators department with a Senior Administrator role. For extended access, add them to Support.
</p>
<br />

<p>
<p align="center"> 
<img width="574" alt="Level II Support " src="https://github.com/MalikS-Github/post-install-config/assets/173410266/300ddd86-1f1b-411d-a6ac-544dfdfa9cac">
</p>
<p>
Step 13: Keep all permissions under the "Permissions" tab the same, and for teams, add Agent 1 to the Level II Support team.
</p>
<br />

<p>
<p align="center"> 
<img width="653" alt="Step 24" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/dca91105-7bb0-4cf3-ae0e-4e8a1d47c59d">
</p>
<p align="center"> 
<img width="650" alt="Step 26" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/9b366ce0-0e7f-4466-9c65-9c4bead97bb6">
</p>
<p>
Step 14: Add Agent 2 to the Support department with an "Expanded Access" role and no extended access.
</p>
<br />

<p>
<p align="center"> 
<img width="575" alt="Level 1 Support" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/bd58af37-cd14-47da-bb56-ca5cf334e480">
</p>
<p>
Step 15: Keep all permissions the same and add Agent 2 to the Level I Support team, then click on "Create."
</p>
<br />

<p>
<p align="center"> 
<img width="573" alt="JWick" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/73fe3b79-1c7f-4db9-b85c-a035cf0033d5">
</p>
<p align="center"> 
<img width="578" alt="JWick 2" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/06eb03c6-aacf-4849-b544-b29640afc35c">

</p>
<p>
Step 16:  Create Agent 3 and choose "Maintenance" as their department, "Senior Administrator" for their role, and no extended access.
</p>
<br />

<p>
<p align="center"> 
<img width="574" alt="Level II Support " src="https://github.com/MalikS-Github/post-install-config/assets/173410266/66dbc82e-a0e6-4d60-8cc7-502af83296ef">
</p>
<p>
Step 17: Add Agent 3 to the Level II Support team and click on "Create."
</p>
<br />

<p>
<p align="center"> 
<img width="647" alt="Step 27" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/3d3dfc6c-86bd-4060-b54c-e16b8e97ea1e">
</p>
<p align="center"> 
<img width="649" alt="Step 28" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/9161cdd8-0c80-492a-883d-74d428781a8f">
</p>
<p align="center"> 
<img width="436" alt="Step 29" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/711f87ae-ac1e-4f59-9f7b-18171962b32a">
</p>
<p>
Step 18: Go to the Agent panel, then click on "Users," and add the users who will be creating support tickets.
</p>
<br />

<p>
<p align="center"> 
<img width="436" alt="Step 29" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/e7378673-21cb-4584-ba7c-9663fa2b590a">
</p>
<p align="center"> 
<img width="431" alt="Step 32" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/deb9ddcc-cde7-45d8-a5ea-c22ec0963050">
</p>
<p>
Step 19: Fill out the text input fields and click "Add user" to create two users.
</p>
<br />

<p align="center"> 
<img width="646" alt="Step 33" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/28d56fab-8f37-4fe9-9330-21fef9135d90">
</p>
<p>
Step 20: Return to the admin panel to create SLAs (service-level agreements).
</p>
<br />

<p>
<p align="center"> 
<img width="649" alt="Step 34" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/6492aa4d-f16c-4c4c-912d-90bb259bfcb7">
</p>
<p align="center"> 
<img width="643" alt="Step 35" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/d9063808-6d09-42db-ad77-34fd10650a79">
</p>
<p>
Step 21: Navigate to "Manage" and then "SLA," and create three distinct SLA plans by clicking "Add new SLA Plan."
</p>
<br />

<p align="center"> 
<img width="649" alt="Step 36" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/e5a1914d-0217-4e72-988a-b12ab06dd9ae">
</p>
<p>
Step 22: Create SLA 1 and name it SEV-A. Set the grace period to one hour on a 24/7 schedule, and then click "Add Plan."
</p>
<br />

<p align="center"> 
<img width="648" alt="Step 38" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/cbdcd197-3508-4ba8-b4b6-42e9e192ef59">
</p>
<p>
Step 23: Create SLA 2 and name it SEV-B. Set the grace period to four hours on a 24/7 schedule.
</p>
<br />

<p align="center"> 
<img width="644" alt="Step 39" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/9d814383-2c14-47a5-b5bc-d5eced440e5f">
</p>
<p>
Step 24: Create the last SLA, which is less severe, and name it SEV-C. Set the grace period to eight hours, Monday through Friday from 8 AM to 5 PM.
</p>
<br />

<p align="center"> 
<img width="649" alt="Step 40" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/8b392bf2-b2ae-46e0-be74-5f1113e95b9d">
</p>
<p>
Step 25: Proceed to create various help topics by clicking on the "Help Topics" tab.
</p>
<br />

<p>
<p align="center"> 
<img width="644" alt="Step 41" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/271641ce-d001-42d3-bd56-8c53486f2e26">
</p>
<p align="center"> 
<img width="647" alt="Step 42" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/e018d0c8-d3c4-4788-97ea-e0e91de63c7a">
</p>
<p>
Step 26: Click on "Add new help topic," name it "Business Critical Outage" and then click "Add topic."
</p>
<br />

<p>
<p align="center"> 
<img width="653" alt="Step 44" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/97fb80f9-30e4-4352-ab3a-274fe63c3ada">
</p>
<p align="center"> 
<img width="649" alt="Step 45" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/7d9f84c8-e174-4c38-aeb4-b908fdef6a04">
</p>
<p align="center"> 
<img width="572" alt="Password Reset" src="https://github.com/MalikS-Github/post-install-config/assets/173410266/2344f3d7-36b6-444a-ad85-541d501e9778">
</p>
<p>
Step 27: Add three more help topics with the following names:
<ul>
  <li>Personal Computer Issues</li>
  <li>Equipment Request</li>
  <li>Password Reset</li>
 </ul> 
</p>
<br />

>osTicket: Ticket Lifecycle Examples</a></p>
It is important to take care of the patient, to be followed by the patient, but it will happen at such a time that there is a lot of work and pain. For to come to the smallest detail, no one should practice any kind of work unless he derives some benefit from it. Do not be angry with the pain in the rebuke, in the pleasure he wants to be a hair from the pain, let him run away from the pain.
</p>
<br />
