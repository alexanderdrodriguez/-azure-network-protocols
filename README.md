<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>Deployment and Configuration Steps</h2>

<p>Section 1: Click “Resource groups” in Microsoft Azure -> Click “Create resource group” -> After typing the resource groups name click “Review + create” -> Type or select “Virtual Machines” -> Select the create button and then click “Azure virtual machine” -> Select the resource group you just created previously -> Type “VM1” as the virtual machine name -> Select “Windows 10” as the image -> Enter and note down a username and password (It’s a must to remember it) -> Check the licensing checkbox then select “Review + create” (leave every option default) -> Create another VM in the same fashion, the only things that are going to be different is you must use the name VM2 and select “Ubuntu” as the image  -> Type and select “Network Watcher” in Azure -> Click “Topology” under “Monitoring” -> Select the resource group you previously </p>
<img src="https://i.gyazo.com/a23d69f7a387af8a49415d0d045e52ee.png">
<img src="https://i.gyazo.com/9d90d8f07497cd25bcc57b9c008e38e0.png">
<img src="https://i.gyazo.com/c8531d3d56e574c09d7327b300c2f918.png">
<img src="https://i.gyazo.com/790599f70a7cf08a963383ec66d488f0.png">
<img src="https://i.gyazo.com/a3ca2866453fd1bf678ed0d4e274f93b.png">
<img src="https://i.gyazo.com/97e4b14f38116fe573bfd57a607425c5.png">
<img src="https://i.gyazo.com/36cc111132c14573eb0cdf4e7c73c930.png">
<img src="https://i.gyazo.com/09f4ee42ebb0aedb731bb8143dd744a4.png">
<img src="https://i.gyazo.com/4ca52fc69563efe897ded83f52837391.png">
<img src="https://i.gyazo.com/17d16485e7416cdb84628afbffe7bacf.png">
<img src="https://i.gyazo.com/2aab57df50b46f8ca04c9071a2db584f.png">
<img src="https://i.gyazo.com/260bcd1c9f157b1afeeb5c312d10a206.png">
<img src="https://i.gyazo.com/12d30aacbf1c43922bf1e012dcdb908a.png">
<img src="https://i.gyazo.com/8790ebfc63b47b1dd5c55dff17ef4166.png">
<img src="https://i.gyazo.com/bb2edcbba4a5c2adaecccd6d05622b46.png">
<img src="https://i.gyazo.com/e47caa07d9edd89ab81d698bb1354a57.png">
<img src="https://i.gyazo.com/fa67460f0941c9f494709f789e0f541d.png">
<img src="https://i.gyazo.com/c500a7c4a79a18f9c2611527ffde4d50.png">
<br />
