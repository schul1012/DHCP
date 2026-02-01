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

<p align="center">
Name the scope. It's fine to name it the same as the IP range for convenience.<br/>
<img width="1248" height="960" alt="image" src="https://github.com/user-attachments/assets/a971d9e9-3779-4b48-a483-32dd72be07c3" />
<br/>
<br/>

<p align="center">
Set the range, length and subnet mask and then click on 'Next'.<br/>
<img width="1170" height="843" alt="image" src="https://github.com/user-attachments/assets/9a37069b-4efc-4b5f-a9bc-8071e625a108" />
<br/>
<br/>

<p align="center">
There is no exclusion for now. Skip it by clicking on 'Next'.<br/>
<img width="510" height="421" alt="image" src="https://github.com/user-attachments/assets/6102da1b-8be9-4119-94ab-483a39bec9f9" />
<br/>
<br/>

<p align="center">
Add the default gateway address and click on 'Next'.<br/>
<img width="507" height="419" alt="image" src="https://github.com/user-attachments/assets/191951a5-4033-4afa-bb8d-c1b5b5a0e87d" />
<br/>
<br/>

<p align="center">
Click on 'Next' repeatedly and then 'Install'.<br/>
<img width="510" height="425" alt="image" src="https://github.com/user-attachments/assets/2503c20b-b4f1-4f2b-95ff-b154c61c53ef" /><br/>
<img width="1171" height="843" alt="image" src="https://github.com/user-attachments/assets/78b56333-dc17-4ea3-b122-662bdbf234db" /><br/>
<img width="1175" height="838" alt="image" src="https://github.com/user-attachments/assets/44e371ec-1483-4b17-af0c-d72bbcaff60d" /><br/>
<img width="642" height="487" alt="image" src="https://github.com/user-attachments/assets/85769149-3bb7-4eee-a3c6-431b2ec46d9e" /><br/>
<br/>
<br/>

<p align="center">
Right click on the server and refresh to make sure that everything is in effect.<br/>
<img width="763" height="543" alt="image" src="https://github.com/user-attachments/assets/3ab7f17c-7bcb-4e6f-8534-3066b17d442d" />
<br/>
<br/>

<p align="center">
Now I can see that the scope under IPv4.<br/>
<img width="1153" height="542" alt="image" src="https://github.com/user-attachments/assets/6330d0d8-43c5-47c2-8bf4-ff154e8febf4" />
<br/>
<br/>





