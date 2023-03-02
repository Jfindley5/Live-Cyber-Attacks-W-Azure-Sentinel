<h1>Live Cyber Attacks W/ Azure Sentinel</h1>

<h2>Description</h2>
In this Lab, we're going to walk through the process how to set up a live virtual machine as a honey pot that will attract live RDP Brute force attacks. The PowerShell script is responsible for parsing out Windows Event Log information for failed RDP attacks using a third party API to collect geographic information about the attakers location.
<br />

<h2>Environments and Utilities Used</h2>
<p>Microsoft Azure <br>
Microsoft Remote Desktop<br>
PowerShell</p>

<h2>In this project, we will</h2>
<p> - Configure and Deploy Azure Resources: Virtual Machines, Azure Sentinel, and Log Analytics Workspace.</p>
<p> - Understand Windows Security Event logs.</p>
<p> - Use PowerShell to extract RDP failed logon logs from Windows Event Viewer.</p>
<p> - Use ipgeolocation.io to observe the  location of the IP Address.</p>
<p> - Create custom logs and custom fields to extract from custom raw log data.</p>
<br>

<h2>Create Virtual Machine and a Resource Group.</h2>
<p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*e1LAuCYNXrsLE6XvptOXSw.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*-JC7PVbxxpJk-_yYsdhlRg.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
 <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*D7_q6jJp9VIXnnHHHNKMWA.png" height="80%" width="80%" alt=""/>
 <br> </p>
 <h2>Microsoft Defender</h2
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*7g_8Xo8gKbRoNkuyCaKicA.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
 <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*7MykTFZ5C_Oe6quY8IOe3Q.png" height="80%" width="80%" alt=""/>
 <br> </p>
 <h2>Deploy Virtual Machine</h2
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*xYfVAKV1g6cuRSQlNVf4qQ.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
 <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*zBkBPesKPY5EMsjNiKBy4g.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*tRDonQyARJG-XHqCRrrK7w.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
 <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*Lva7IPDfoGLkkVputxyypA.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*7k1dl_t69F6KQtcy8ch7Ww.png" height="80%" width="80%" alt=""/>
 <br> </p>
 <h2>Configure Firewall</h2
 <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*K16jC5mJqHG6sMQ_iqIE4A.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*TJ04uuZ9WYnC_Vu4T72RFw.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
  <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*W92exlOixQJjs4ix8KR7Mg.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*RrezgezktXY9VQEXOKQe1A.png" height="80%" width="80%" alt=""/>
 <br> </p>
 <h2>PowerShell Script</h2
  <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*kHIBQtBpqLXKQCS7blkivg.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*sDfHqDZh6_vi8HFJqp3ZDw.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
  <p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*9VxawHSnHh93E_8kiMVL5A.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*hPaXfzZI9W-ozd-CKqP2nA.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
  <h2>Create custom log in Analytic Workspace</h2
  <p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*tJnZRpGh9zYFLfcqjLvNKA.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*7vfBD6yeZWRNCADsPuGQAA.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
  <p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*a0m5qttCUb3UzKqrwSJT6g.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*2-pELJUx_X0wSdw5zGfLjg.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
   <p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*akQUSqI_1ZO3-E68FljViQ.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*emjLA50gwcc6dkrDfJ1S4Q.png" height="80%" width="80%" alt=""/>
 <br> </p>

   <p align="center">
<img src=" https://miro.medium.com/v2/resize:fit:1400/format:webp/1*P20GJuHz61za4WvfDucitQ.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*tFYjDeBEMmGlJMiX5w3THg.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
 <h2>Set Up Map in Sentinel</h2
   <p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*vC1gnf9UtVNq6Tl_YFs1qg.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*ZV1DvrR5tYXzev82Sv4V3g.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
 
