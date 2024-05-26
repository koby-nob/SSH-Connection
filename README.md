-  <b>Microsoft Azure VM</b>
- Establish SSH connection between Microsoft Azure Virtual Machines
- This project outlines steps and process for establishing SSH connections between two virtual Machines.

<h2>Environments and Technologies Used</h2>

-  Microsoft Azure (Virtual Machines named: VM1 & VM2)
-  Remote Desktop

<h2>Operating System Used </h2>

- Windows 10 Pro versopm 22H2
  
- Ubuntu Server 20.04 LTS Linux

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/RHCEC5x.png"
</p>
<p>
      
  
      - Resource Group created (RG-Lab 5 for the purpose of this project)
      - Select the virtual Machine(VM1) tab and create a the first VM for Linux server: Ubuntu Server. 

<p>
<img src="https://i.imgur.com/UW3RPRY.png"
</p>
<p>

       - Select the virtual Machine(VM2) tab and create a the first VM for Windows 10 Pro. 


<p>
<img src="https://i.imgur.com/Bo4vMG3.png"  
</p>
<p>
    
      - From your main PC, select the Remote Desktop connection tool.
      - Type the Public IP of VM2: 20.84.79.47 to establish Remote Desktop Connection.
<p> 
<img src="https://i.imgur.com/EbV5wRN.png"
</p>
<p>

      - Open the Powershell from windows start button

<p>
<img src="https://i.imgur.com/3fUxgUr.png"
</p>
<p>
       
       - (for the purpose of this project, Windows username for VM1: kobnob, Public IP:20.51.197.27)
       - Type: ssh kobnob@20.51.197.21 + ENTER

<p>
<img src="https://i.imgur.com/WUA2qEn.png"
<p>
</p>

       - Once SSH connection is established for VM1 which is a Ubuntu Linux Server
       - Type these Linux command below to confirm the connection.
       - Type: pwd + Enter (This command will display the current working directory)
       - Type: uname -a + Enter (This command will display the current Linux version and the date and time the connection was established)
