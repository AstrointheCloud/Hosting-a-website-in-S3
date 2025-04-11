# Hosting-a-website-in-S3
 ### [YouTube Demonstration](https://www.youtube.com/watch?v=yknp0-ZD1UM)

<h2>Description</h2>
This project is about setting up a static website on Amazon Web Services (AWS) using the Free Tier. The idea is to host basic web content—like HTML files, images, and other media—using Amazon S3. S3 is a simple, scalable, and cost-effective solution, making it perfect for hosting static sites without dealing with the complexity of the servers

<br />


<h2> Utilities Used</h2>

- <b>AWS Free Tier Account</b> 
- <b>Website files</b>

<h2>Step by Step Walkthrough:</h2>

<p align="center">
Launching the AWS Free Tier Account and opening an S3 bucket <br/>
<img src="https://i.imgur.com/fEux6NT.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Choosing the Region for the S3 Instance:  <br/>
 
<img src="https://i.imgur.com/fcQHRFY.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Creating the Instance in S3:  <br/>
 
<img src="https://i.imgur.com/aorowFr.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />

<img src="https://i.imgur.com/D123ppK.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />

<img src="https://i.imgur.com/gcbzibR.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Voila, the instance was created successfully  <br/>
<img src="https://i.imgur.com/avhFcR5.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Picking up the Website Files and Adding them to the Instance in S3: <br/>
<img src="https://i.imgur.com/PSbHhiO.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Uploading the Website Files to the Instance in S3: <br/>
<img src="https://i.imgur.com/I9uwQAu.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Uploaded the website files in S3: <br/>
<img src="https://i.imgur.com/jYQdnIp.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Configuring the website hosting:  <br/>
<img src="https://i.imgur.com/LuYTEyJ.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Opening the bucket astrointhecloud2:  <br/>
<img src="https://i.imgur.com/E3XAqHs.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
<img src="https://i.imgur.com/81gG3t4.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Editing the Static Website Hosting:  <br/>
<img src="https://i.imgur.com/vYuMf1H.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Editing the configuration of the Static Website Hosting:  <br/>
<img src="https://i.imgur.com/aIJ2IyU.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Error 403 Forbidden because it doesn't have the permissions:  <br/>
<img src="https://i.imgur.com/gxiYo8O.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Making public the website using ACL:  <br/>
<img src="https://i.imgur.com/vFj8xN2.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Editing Public Access:  <br/>
<img src="https://i.imgur.com/Zw7iNdJ.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Successfully edited Public Access:  <br/>
<img src="https://i.imgur.com/0RdBFs6.png" height="80%" width="80%" alt="S3 Static Website"/>
<br />
<br />
Finally, refreshing the link and the website should be up and running  <br/>
<img src="https://i.imgur.com/WuBZbc5.png" height="80%" width="80%" alt="S3 Static Website"/>

<h2>Comments</h2>
This project was quite fun. I really enjoyed working on it, struggling, erasing all 10 times, and trying again, and understanding the ACLs, S3, and how they are the appropriate way to ensure a static website is hosted correctly in S3. 

<h2>Learning Resources</h2>:

- <b>Udemy</b>

- <b>Nextwork.org</b> 
- <b>AWS Free Tier</b> 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

