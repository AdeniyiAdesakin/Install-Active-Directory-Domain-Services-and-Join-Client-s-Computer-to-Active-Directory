<h1>Active Directory Domain Services Installation and Joining Client's Computer to ADDS</h1>
<p>This tutorial outlines how to install Window's Active Directory Domain Services - a directory service used in Windows-based networks to manage and organize resources such as computers, users, groups, and services also how to join a client's computer to Active directory.<br/></p>

<P>1. From the server manager dashboard on Windows server 2019, click on Manage and on Add roles and Features</P>
<p align="center"><img src="https://i.imgur.com/BFw3fUz.png" height="50%" width="50%"/>

<p>2. On the before you begin screen, just click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/gaMZiFi.png" height="50%" width="50%"/>

<p>3. On the Installation Type screen, make sure the Role-based or feature-based installation is selected, then click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/ZvY3YRt.png" height="50%" width="50%"/>

<p>4. On the Select destination server screen, make sure the select a server from the server pool is selected and select the server you are trying to install Adds from the server pool, then click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/Xq8ggfi.png" height="50%" width="50%"/>

<p>5. On the select server roles screen, select the second option(Active Directory Domain Services) and click on add features from the pop-up screen, then click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/FJXu3HC.png" height="50%" width="50%"/>

<p>6. On the select features screen, just click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/6Ri1r9H.png" height="50%" width="50%"/>

<p>7. On confirm installation selections, just click on INSTALL and wait for the installation to complete. </p>
<p align="center"><img src="https://i.imgur.com/qgNK3C5.png" height="50%" width="50%"/>

<p>8. After the installation is complete, from the notification, click on promote the server to a domain controller</p>
<p align="center"><img src="https://i.imgur.com/QxcyWQO.png" height="50%" width="50%"/>

<p>9. On the Deployment configuration screen, select add a new forest and enter your desired domain name in the Root domain name box, then click NEXT. </p>
<p align="center"><img src="https://i.imgur.com/qhMIfKw.png" height="50%" width="50%"/>

<p>10. On the Domain Controller Options screen, Input password and confirm password, then click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/W7ujg6C.png" height="50%" width="50%"/>

<p>11. On the Additional options screen, leave your domain name in the NetBIOS domain name and click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/TvIq19K.png" height="50%" width="50%"/>

<p>12. On the Paths screen, leave it at default and click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/VvvvYWw.png" height="50%" width="50%"/>

<p>13. On the Review Options, click NEXT.</p>
<p align="center"><img src="https://i.imgur.com/S3odSml.png" height="50%" width="50%"/>

<p>14. On the Prerequisites Check, click INSTALL .</p>
<p align="center"><img src="https://i.imgur.com/3Lto4nb.png" height="50%" width="50%"/>

<p>15. On the Installation page, just wait for the installation to complete.</p>
<p align="center"><img src="https://i.imgur.com/l82jh6v.png" height="50%" width="50%"/>



<br>
<br>
<br>
<br>
<br>
<br>



<h1>Joining Windows 11 (client's computer) to ADDS</h1>
<p>To join a client's computer to Active Directory Domain Services(ADDS), I did the following<p>

<p>1. From the client's computer , go to This PC, right-click and select on properties.</p>
<p align="center"><img src="https://i.imgur.com/AavnsIH.png" height="50%" width="50%"/>

<p>2. On the about page, click on Domain or workgroup</p>
<p align="center"><img src="https://i.imgur.com/E8xSesk.png" height="50%" width="50%"/>

<p>3. On the system’s properties’ screen, in the the computer name tab, click on change</p>
<p align="center"><img src="https://i.imgur.com/kVdB6eC.png" height="50%" width="50%"/>

<p>4. On the Computer name/Domain changes, click the “Member of” to be Domain and input your domain name, then click OK.</p>
<p align="center"><img src="https://i.imgur.com/9V2xVK0.png" height="50%" width="50%"/>

<p>5. This next screen pops up for you to enter name and password of an account with permission to join domain, enter the required info and click OK.</p>
<p align="center"><img src="https://i.imgur.com/RKRRCVQ.png" height="50%" width="50%"/>

<p>6. Then you will be required to restart your computer to apply the changes, just click OK.</p>
<p align="center"><img src="https://i.imgur.com/VlT6HCs.png" height="50%" width="50%"/>


<br>
<br>
