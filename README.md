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

<p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*e1LAuCYNXrsLE6XvptOXSw.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*-JC7PVbxxpJk-_yYsdhlRg.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
 <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*D7_q6jJp9VIXnnHHHNKMWA.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*7g_8Xo8gKbRoNkuyCaKicA.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
 <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*7MykTFZ5C_Oe6quY8IOe3Q.png" height="80%" width="80%" alt=""/>
 <br> </p>
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
 
  <p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*kHIBQtBpqLXKQCS7blkivg.png" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="https://cdn-images-1.medium.com/max/1600/1*sDfHqDZh6_vi8HFJqp3ZDw.png" height="80%" width="80%" alt=""/>
 <br> </p>
 
  <p align="center">
<img src="" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="" height="80%" width="80%" alt=""/>
 <br> </p>
 
  <p align="center">
<img src="" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="" height="80%" width="80%" alt=""/>
 <br> </p>
 
  <p align="center">
<img src="" height="80%" width="80%" alt=""/>
 <br> </p>
<p align="center"> 
<img src="" height="80%" width="80%" alt=""/>
 <br> </p>
