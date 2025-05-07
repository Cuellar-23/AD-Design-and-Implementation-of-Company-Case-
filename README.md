<h1>AD-Design-and-Implementation-of-Company-Case</h1>

<h2>Description</h2>
 In this project I will create a simulated enterprise network by configuring two virtual machines (VMs): one running Windows Server 2022 and the other Windows 10 using Hyper-V. Once both machines were created in Hyper-V, I configured the Machines, assigning computer names and IP addresses. After that I performed a ping test ensuring both machines can communicate with one another. Next, I installed the Active Directory Domain Services (AD DS) role on the Windows Server Machine, promoted it to a domain controller, and joined the Windows 10 Machine to the newly created domain.  
<br />

<h2>Project walk-through:</h2>

<p align="center">
Creation of Orginizational Unit for the Company "Blue Water" : <br/>
<img src="https://github.com/Cuellar-23/AD-Design-and-Implementation-of-Company-Case-/blob/main/Screenshot%202025-05-07%20102230.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The creation of Security Groups for every department:  <br/>
<img src="https://github.com/Cuellar-23/AD-Design-and-Implementation-of-Company-Case-/blob/main/Screenshot%202025-05-07%20132921.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creation of User accounts  <br/>
<img src="https://github.com/Cuellar-23/AD-Design-and-Implementation-of-Company-Case-/blob/main/Screenshot%202025-05-07%20133205.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding Users to Groups:  <br/>
<img src="https://github.com/Cuellar-23/AD-Design-and-Implementation-of-Company-Case-/blob/main/Screenshot%202025-05-07%20134809.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The section of the Active Directory Domain Services role on DC01:  <br/>
<img src="https://github.com/Cuellar-23/Creation-of-Domain-controller-and-VM/blob/main/Screenshot%202025-05-07%20094759.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Server Manager dashboard after Active Directory role is added and DC01 is promoted to Domain Controller:  <br/>
<img src="https://github.com/Cuellar-23/Creation-of-Domain-controller-and-VM/blob/main/Screenshot%202025-05-07%20095147.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creation of my Domain jcuellar.local and succesful join of PC01 to the Domain :  <br/>
<img src="https://github.com/Cuellar-23/Creation-of-Domain-controller-and-VM/blob/main/Screenshot%202025-05-07%20095712.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
