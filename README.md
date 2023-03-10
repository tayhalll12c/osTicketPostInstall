<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This demonstration outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Login to osTicket as an admin
- Configure roles 
- Configure departments 
- Configure teams 
- Allow anyone to create tickets 
- Configure agents
- Configure users
- Configure SLA
- Configure help topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/2rjP34p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login with the credentials that were created when installing osTicket. 
</p>
<br />

<p>
<img src="https://i.imgur.com/q4hJML2.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the admin panel, under Agents and Roles, click 'Add New Role'  
</p>
<br />

<p>
<img src="https://i.imgur.com/nvnSUrW.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the role "Supreme Admin"  
</p>
<br />

<p>
<img src="https://i.imgur.com/BBolgNL.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/U3txiMh.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/tSVeWNm.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the purpose of this demonstration, "Supreme Admin" will be granted all permissions.   
</p>
<br />

<p>
<img src="https://i.imgur.com/oXo6gug.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click 'Add New Department' 
</p>
<br />

<p>
<img src="https://i.imgur.com/bybCNhy.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the department 'System Administrators' and leave the rest of the settings on default (create department right away).   
</p>
<br />

<p>
<img src="https://i.imgur.com/Y2RzDko.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click 'Add New Team'   
</p>
<br />

<p>
<img src="https://i.imgur.com/4JLd8oY.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the team 'Level II Support'   
</p>
<br />

<p>
<img src="https://i.imgur.com/4G2OFKh.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add the person to the team, and then create.    
</p>
<br />

<p>
<img src="https://i.imgur.com/3NgyMph.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ensure that this box is unchecked, so anyone can create tickets.     
</p>
<br />

<p>
<img src="https://i.imgur.com/16ZYxrz.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click 'Add New Agent'.      
</p>
<br />

<p>
<img src="https://i.imgur.com/qE0YRtl.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set a name, username, and email (samples are used in this case). Then, click 'Set Password'.       
</p>
<br />

<p>
<img src="https://i.imgur.com/gWgPzz8.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Leave these boxes unchecked, type in a password, and click 'Set'.        
</p>
<br />

<p>
<img src="https://i.imgur.com/zQl7QsJ.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set departments.         
</p>
<br />

<p>
<img src="https://i.imgur.com/EboDW6L.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set permissions.          
</p>
<br />

<p>
<img src="https://i.imgur.com/MEd86UF.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set team and create agent.          
</p>
<br />

<p>
<img src="https://i.imgur.com/7Oiei1E.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Repeat the process with another agent.           
</p>
<br />

<p>
<img src="https://i.imgur.com/SFFASJR.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select different departments if desired, and then create.             
</p>
<br />

<p>
<img src="https://i.imgur.com/06OLNIZ.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Switch to the Agent Panel.              
</p>
<br />

<p>
<img src="https://i.imgur.com/E7smb06.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click 'Add User'.               
</p>
<br />

<p>
<img src="https://i.imgur.com/pzzDgN9.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Type in user credentials and add.                
</p>
<br />

<p>
<img src="https://i.imgur.com/R2pG2fo.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Repeat the process with another user.                 
</p>
<br />

<p>
<img src="https://i.imgur.com/7b9Kd4g.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Return to the Admin Panel.                 
</p>
<br />

<p>
<img src="https://i.imgur.com/4yLenyX.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click 'Add New SLA Plan'.                 
</p>
<br />

<p>
<img src="https://i.imgur.com/MDOdkfp.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enter information for a service-level agreement and click 'Add Plan'.                  
</p>
<br />

<p>
<img src="https://i.imgur.com/bE6tcte.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Repeat the process with a different SLA.                  
</p>
<br />

<p>
<img src="https://i.imgur.com/TesRjgo.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Repeat the process with a different SLA.                  
</p>
<br />

<p>
<img src="https://i.imgur.com/MQhXriC.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click 'Add New Help Topic'.                   
</p>
<br />

<p>
<img src="https://i.imgur.com/Ex27fvT.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enter information for a help topic and add it.                    
</p>
<br />

<p>
<img src="https://i.imgur.com/9LB7444.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Repeat the process with other help topics.                     
</p>
<br />

<p>
<img src="https://i.imgur.com/c4L76ZW.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Repeat the process with other help topics.                     
</p>
<br />

<p>
<img src="https://i.imgur.com/Whd4C7A.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Repeat the process with other help topics.                     
</p>
<br />
