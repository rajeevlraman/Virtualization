<h1>Virtualization</a></h1>

<h2>👨‍💻 Virtualization Platforms</h2>
Hey, starting a homelab with a particular Virtualization platform was the initail plan. But then, had to experiment with all the available platforms. VMWare was the Requirement of the course as the labs were based on the platform. It was provide as a latest licenced copy with full functionality. but the fact that it will expire after the course was the reason to try Virtual box from Oracle. Then there was proxmox another open source and seemed to be popular among homelab enthusiasts. Each has its own pros and cons. So I had to experiment to understand each platform and its features and the way the network settings have to be configured, also the settings for each VM, and its storage. At this point it was only underastandable that I had to know how to migrate Vm's between platforms. so below I have a brief description of each platform and a screenshot of my VM's. By the way I use both Virtual Box and proxmox. finally I used Hyper-V to run windows environoments. Microsoft has a complete lab setup which lets you play around with a fully setup domain controller and clients already joined to it. Ok then thats for the intro, below you can get a feel of the lab I setup for my understanding. Hope you can have you own and enjoy the journey to understand managing a network and its elements and also manage and harden security control. My ultimate goal is to understand the analysis of logs and monitoring softwares and create my own dashboards to give me the best insight and help me in provide monitoring and mitigation solutions.<br><br>

<img src="images/simple-icons--virtualbox(1).png" alt="The Virtual Box" width="100" height="100">**Labsetup - 1**<br/> Environment is set up with three different topologies.
 Environment is set up with three different topologies. One is based on the topology and older machines used in the Holmesglen Netlab activities. the second lab is b ased on a SIEM Security Information and Event Management perspective. This lab was built to simulate a SOC analyst environment to conduct all sorts of log monitoring and analysing various attacks which is carried out by Kali Linux from an internal network and outside the network. the third lab was a openvpn lab, built with openvpn.<br><br>
***The Proxmox lab*** environment is built to understand the baremetal server environment and various linux based installations. It is a general lab environment with a SOC analyst perspective and to understand the Proxmox platform.<br><br>
***The Hyper-V Lab*** environment is built again to understand the platform and aslo to experiment with various windows scenarios. I have used this lab most extensively to setup and manage Domain Controller, Active Directory services, IIS(Internt Information Services) Web server, and Microsoft Exchange server. windows 11 and Office 365 Deployment Lab kit is a wonderful lab to learn a lot on deployment and configuration services.<br><br>
  <b><img align="center" src="https://i.imgur.com/CsaHQku.png" /></b><br/>  
  - <b>Labsetup - 1</b><br/>
  
  <b><img align="center" src="https://i.imgur.com/RYJxINY.png" /></b><br/>
  - <b>Labsetup - 2</b><br/>
  
  <b><img align="center" src="https://i.imgur.com/7to5deQ.png" /></b><br/>
  - <b>Labsetup - 3</b><br/>
  
  <b><img align="center" src="https://i.imgur.com/6htDcD8.png" /></b><br/>
  <h2>👨‍💻 Proxmox</h2>
  - <b>Proxmox Lab setup</b><br/>

  <b><img align="center" src="https://i.imgur.com/gCt1c7f.png" /></b><br/>
  <h2>👨‍💻 Hyper-V</h2>
  - <b>Hyper-V Lab setup</b><br/>

  <b><img align="center" src="https://i.imgur.com/kyBDOLi.png" /></b><br/>


