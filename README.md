<p align="center"> <img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployment in the Cloud (Azure) Part 1</h1>

<h1>Overview</h1>

This is part one of a series of tutorials demonstrating the deployment of Active Directory in a cloud setting. In this tutorial we will be covering how to configure your Domain Controller (DC-1) and a single client machine (Client-1). Figure 1.1 shows the machine layout we will be using in this series.<br />

![image](https://github.com/user-attachments/assets/7e9b3436-ff3b-4947-a250-6dcf06df7bef)
<p align="center">Figure 1.1</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 Pro (22H2)

<h2>Deployment and Configuration Steps</h2>

<h3>Create a Recourse Group</h3>

![image](https://github.com/user-attachments/assets/7e1573f1-72fb-4990-b665-20066b0bceee)

![image](https://github.com/user-attachments/assets/13963463-683f-40e3-9661-67717092f988)

![image](https://github.com/user-attachments/assets/be042d69-57c5-4aeb-9b84-fd04c54848c6)

<br />
<h3>Create a Virtual Network</h3>

![image](https://github.com/user-attachments/assets/38ab43ce-1c49-43e4-90af-1a6dfd593fe5)

![image](https://github.com/user-attachments/assets/cb441be6-bb8c-4237-a6ef-e9dafac23bec)

![image](https://github.com/user-attachments/assets/0f8d6f87-45fc-449d-9969-20a3c7098831)

<br />
<h3>Deploy the Domain Controller (DC-1)</h3>

![image](https://github.com/user-attachments/assets/76435c5f-227f-4084-b5b6-dc78582d3732)

![image](https://github.com/user-attachments/assets/e8158bdb-c513-48e0-b055-043e93301a76)

![image](https://github.com/user-attachments/assets/2eb23043-32ee-4b47-a976-5f4cf7c7c359)

![image](https://github.com/user-attachments/assets/6cecc3db-7882-45d6-a59d-10cfb7213e34)

![image](https://github.com/user-attachments/assets/2125b82d-759c-41a4-a397-6343978dedd6)

![image](https://github.com/user-attachments/assets/fe61b4dc-502f-44fc-ba38-c5975dfb2c17)

<br />
<h3>Deploy the Client Machine (Client-1)</h3>

![image](https://github.com/user-attachments/assets/1d15d89b-f4cd-4151-a927-c3f8d18183db)

![image](https://github.com/user-attachments/assets/1c168cb4-b128-4c22-9094-15ceb28100a5)

![image](https://github.com/user-attachments/assets/601f0a42-b4f1-4199-9f73-3c0bf54e5d52)

![image](https://github.com/user-attachments/assets/2d72a840-4a7c-4a8c-afb7-9116dbabe1b6)

![image](https://github.com/user-attachments/assets/89285296-c0bb-4c02-be04-924c5b728032)

<br />
<h3>Configure DC-1's Network Settings</h3>

![image](https://github.com/user-attachments/assets/ec9d0937-38e7-4e52-bc54-ffa08c51c2cd)

![image](https://github.com/user-attachments/assets/9cd08615-e591-4fbb-bd30-b8609dd0d4fd)

![image](https://github.com/user-attachments/assets/4a8e9681-06eb-4c5a-805c-f076088424c4)

![image](https://github.com/user-attachments/assets/1f81844b-eebc-4a27-a321-7d14f4012fb2)

![image](https://github.com/user-attachments/assets/23c44884-5ea0-4268-b05f-a4fccd2523b1)

![image](https://github.com/user-attachments/assets/e13ef96b-524d-448d-ab82-98df315a3485)

![image](https://github.com/user-attachments/assets/02057528-a82c-4992-98da-4c3ce1e0e50b)

![image](https://github.com/user-attachments/assets/4748b727-4a03-4216-8112-d0d313b0961d)

![image](https://github.com/user-attachments/assets/b8ab2e1b-c794-4f70-bab6-6ff598ef1d76)

![image](https://github.com/user-attachments/assets/db91ecc6-6c8b-498d-944b-0610dffd8c8c)

![image](https://github.com/user-attachments/assets/55ef0146-7519-498a-abb8-7b6c69225189)

<br />
<h3>Configure Client-1's DNS Settings</h3>

![image](https://github.com/user-attachments/assets/225d6db4-3c22-4f57-bef8-5fe90a8db974)

![image](https://github.com/user-attachments/assets/3ee57d6d-444a-40ff-9095-01959b3c10a5)

![image](https://github.com/user-attachments/assets/13e4c908-bdfc-44e0-956c-2f09b75a965c)

![image](https://github.com/user-attachments/assets/bd7e5396-e9d7-4616-ac19-1445039bcf27)

<br />
<h3>Verify DNS Connectivity Between DC-1 and Client-1 (Ping)</h3>


![image](https://github.com/user-attachments/assets/f81de116-f54f-4ed8-89e7-458e689d2ee7)

![image](https://github.com/user-attachments/assets/e9ee0de9-048b-4e1f-b05e-76a664eccee1)

![image](https://github.com/user-attachments/assets/919dc0bd-a30d-466b-996f-f04e1e34e8f3)

![image](https://github.com/user-attachments/assets/1c89c9fa-e2ec-4720-b84f-b5d406fbdcc1)

![image](https://github.com/user-attachments/assets/a96fa914-ba27-413f-9a31-10c360aaa448)

![image](https://github.com/user-attachments/assets/3dc91209-07a4-497c-a162-d6b8aba4f126)

![image](https://github.com/user-attachments/assets/83ca570a-2c6d-4dd6-ad4b-fe1544dab204)

![image](https://github.com/user-attachments/assets/98b71a37-3d47-4a06-9b92-74910d2af1dc)

![image](https://github.com/user-attachments/assets/01b1423e-9f7d-45fe-b722-13a7d4f9a703)

<h3>Conclusion</h3>
<pre>
At this stage, we have successfully:
  1. Created both a Resource Group and a Virtual Network.
  2. Deployed an configured DC-1 as the Domain Controller.
  3. Deployed Client-1 and updated its DNS settings.
  4. Verified connectivity between the two machines.
</pre>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
