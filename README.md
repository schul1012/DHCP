<h1>DHCP</h1>

<h2>Description</h2>
A walkthrough of configuring DHCP on the domain controller.
<br />


<h2>Prerequisites</h2>
- <b><a href="https://github.com/schul1012/Setting-up-network-of-a-domain-controller-and-a-client/tree/main">Setting up a Domain Controller and a Client, Using VirtualBox</a></b><br/>
- <b><a href="https://github.com/schul1012/Active-Directory-Domain-Setup/blob/main/README.md">Active Directory Domain Setup</a></b><br/>
- <b><a href="https://github.com/schul1012/NAT/tree/main">RAS and NAT configuration</b><br/>


<h2>Environments Used</h2>

- <b>Windows 2019</b>

<h2>Walkthrough</h2>

<p align="center">
On the Server Manager of the server VM, click on 'Add roles and features'.<br/>
<img width="1245" height="959" alt="image" src="https://github.com/user-attachments/assets/f1922e6a-3e3f-45fd-91b9-214af5c96f39" />
<br/>
<br/>

<p align="center">
Skip to Server Roles by clicking on 'Next' a couple of times. Select DHCP Sever. Click on 'Add Features' on the popup.<br/>
<img width="1035" height="690" alt="image" src="https://github.com/user-attachments/assets/bcccd380-6aa6-4306-a82a-ad99d4f6eef5" /><br/>
<br/>
<br/>

<p align="center">
Click on 'Install' and then 'Close' once the installation is finished.<br/>
<img width="783" height="559" alt="image" src="https://github.com/user-attachments/assets/243ca3d1-0779-4af2-b693-470bf4132ccd" /><br/>
<img width="778" height="558" alt="image" src="https://github.com/user-attachments/assets/1505be98-8e99-4650-a397-04bbeef5aa6d" />
<br/>
<br/>

<p align="center">
Click on 'Tools' and then 'DHCP' on Server Manager.<br/>
<img width="1249" height="963" alt="image" src="https://github.com/user-attachments/assets/d51a3308-4e7d-4c71-b107-9b2849146972" />
<br/>
<br/>

<p align="center">
Right-click on IPv4 under the domain and Left-click on 'New Scope'.<br/>
<img width="1242" height="960" alt="image" src="https://github.com/user-attachments/assets/fded3932-9f78-46c9-98b4-87745616b792" />
<br/>
<br/>

<p align="center">
New Scope Wizard starts. Click on 'Next'.<br/>
<img width="1181" height="840" alt="image" src="https://github.com/user-attachments/assets/c482b8ab-231d-4cc3-9632-8af30db54c00" />
<br/>
<br/>

<img width="1248" height="960" alt="image" src="https://github.com/user-attachments/assets/a971d9e9-3779-4b48-a483-32dd72be07c3" />

