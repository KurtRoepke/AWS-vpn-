# AWS-vpn-
<h1>AWS openvpn server</h1>

 

<h2>Description</h2>
<b>In this repository we go over creating an open vpn server using AWD's cloud. Next i explain how to ssh into that machine by using windows powershell and, finally how to log into the admin and client accounts from the web browser.</b>


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
<img src="images/vpn1.png" height="70%" width="70%"/>




Next scroll down to quickstart and choose browse more AMI's.
<img src="images/vpn2.png" height="70%" width="70%" />




After go to AWS marketplace AMI's and, choose the open vpn option.
<img src="images/vpn3.png" height="70%" width="70%"  />




 Go to the bottom right corner and press subscribe now.
<img src="images/vpn4.png" height="70%" width="70%" />


 
 
 In instance type select the t.2 micro for the free tier then scroll down to the bottom and choose launch instance.
<img src="images/vpn5.5.png" height="70%" width="70%"  />




You will be asked to create a new key pair. Create a new name in the box provided. Make sure the keypair file was downloaded.
<img src="images/vpn6.png" height="70%" width="70%"  />




Next click on the instance and then choose connect.
<img src="images/vpn8.png" height="70%" width="70%"/>




After connecting to the instance go to the ssh client and copy the code example.
<img src="images/sshwebn.png" height="70%" width="70%" />




 Open powershell and paste the command and, change the location of the file if needed
<img src="images/sshpowern.png" height="70%" width="70%"  />



 
 Next its going to want you to log in with a new username it provides so using the same command replace root with the new username.
<img src="images/vpn11n.png" height="70%" width="70%" />


 

 Just keep pressing enter to select the default settings remeber the https url we will need that to log in later.
<img src="images/vpn11.5n.png" height="70%" width="70%"  />



 
 Your password will be auto generated if you dont put one in yourself or you can just change it later using the passwd comand 
<img src="images/passwordn.png" height="70%" width="70%"  />



Next put your url in the search bar you will get a prompt saying you connection is not private its ok just click andaved and proceed.
<img src="images/warning.png" height="70%" width="70%"  />-->



log into the vpn admin account and change the setting to route all traffic through the vpn.
<img src="images/vpnsettings.png" height="70%" width="70%"  />




 After, log into the client account is the same just delete the admin in the search bar.
<img src="images/userpor2.png" height="70%" width="70%" />




Next you will need to download the application for your os. Microsoft will give you a warning but its ok just keep hitting next
<img src="images/eula.png" height="70%" width="70%"/>




Finaly click the openvpn icon on your desktop and turn it on and, after you log in you are done and secure.
<img src="images/finallogin.png" height="70%" width="70%" />


 

