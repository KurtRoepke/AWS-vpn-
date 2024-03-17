# AWS-vpn-
<!--<h1>AWS openvpn server</h1>

 

<h2>Description</h2>
<b>In this repository we go over creating an open vpn server using AWD's cloud. Next i explain how to ssh into that machine by using windows powershell and, finaly how to log into the admin and client accounts from the web browser.</b>


<h2>Utilities Used</h2>

- <b>powershell</b> 
- <b>linux terminal</b> 
- <b></b>

<h2>Environments Used </h2>

- <b>chrome</b> (21H2)
- <b>AWS console</b> (21H2)
- <b></b> (21H2)

<h2>Program walk-through:</h2>

First log into your AWS account scroll down to launch a virtual machine ec2.
<img src="Images/1.png" height="70%" width="70%"/>



Next scroll down to quickstart and choose browse more AMI's.
<img src="Images/2.png" height="70%" width="70%" />



After go to AWS marketplace AMI's and, choose the open vpn option.
<img src="Images/3.png" height="70%" width="70%"  />



 select subscribe now.
<img src="Images/4.png" height="70%" width="70%" />


 
 In instance type select the t.2 micro for the free tier then scroll down to the bottom and choose launch instance.
<img src="Images/5.png" height="70%" width="70%"  />



You will be asked to create a new key pair create a new name in the box provided.
<img src="Images/6.png" height="70%" width="70%"  />



Make sure the keypair was added to your downloads it should be a .pem file and, launch instance.
<img src="Images/7.png" height="70%" width="70%" />

Next click on the instance and then choose connect.
<img src="Images/8.png" height="70%" width="70%"/>


next go to ssh client and copy the example.
<img src="Images/9.png" height="70%" width="70%" />



 After that open powershell and paste the command and, change the location of the file if needed
<img src="Images/10.png" height="70%" width="70%"  />



Next its going to want you to log in as another user so using the same command replace root with the new user.
<img src="Images/11.png" height="70%" width="70%" />


 
Next just keep pressing enter to select the default settings remeber the https url we will need that to log in later.
<img src="Images/11.png" height="70%" width="70%"  />



your password will be auto generated if you dont put one in yourself.
<img src="Images/.png" height="70%" width="70%"  />


Next add your url here it will prompt you saying your connection is not private its ok.
<img src="Images/12.png" height="70%" width="70%"  />-->


log into the vpn admin account and change the setting to route all traffic through the vpn.
<img src="Images/6.png" height="70%" width="70%"  />



Next to log into the vpn client account just type in the ip address and the port number.
<img src="Images/7.png" height="70%" width="70%" />

next it will ask you to download the application for your os microsoft will give you a warning the click download anyway.
<img src="Images/8.png" height="70%" width="70%"/>



<img src="Images/9.png" height="70%" width="70%" />



 
<img src="Images/10.png" height="70%" width="70%"  />




<img src="Images/11.png" height="70%" width="70%" />


 
<img src="Images/5.png" height="70%" width="70%"  />




<img src="Images/6.png" height="70%" width="70%"  />


<img src="Images/7.png" height="70%" width="70%"  />-->

-->
-->
