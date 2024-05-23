<h1>Pi-Hole</h1>


<h2>Description</h2>
Pi-Hole as virtual machine inside of Proxmox - In Progress

<h2>Steps Taken</h2>
<p align="center">
Ubuntu 22.04 lxc<br/>
<img src="https://imgur.com/Me9bKCa.png" height="80%" width="80%" alt="Ubuntu lxc in Proxmox"/>
<br/>
<br/>
Set ip to 192.168.0.2/24 in the LXC setings
<img src="https://imgur.com/DSpZL8D.png" height="80%" width="80%" alt="Network Settings in Proxmox"/>
<br/>
<br/>
Immediatly ran update && upgrade
<img src="https://imgur.com/Me9bKCa.png" height="80%" width="80%" alt="update && upgrade"/>
<br/>
<br/>
Ran the wget command from pi-hole.net
<img src="https://imgur.com/tywgtUu.png" height="80%" width="80%" alt="wget command"/>
<br/>
<br/>
It's working... set my laptop to the DNS of pi-hole
<img src="https://imgur.com/UA7RfJu.png" height="80%" width="80%" alt="Pi-hole install completed"/>
<br/>
<br/>
<img src="https://imgur.com/eLw3Sak.png" height="80%" width="80%" alt="Pi-hole running"/>
<br/>
<br/>
Set my router interface to the DNS of pi-hole 
<img src="https://imgur.com/a41syQ0.png" height="80%" width="80%" alt="ISP Provided router DNS Map"/>
<br/>
<br/>
<img src="https://imgur.com/3y6RQLq.png" height="80%" width="80%" alt="DHCP and DNS"/>
<br/>
<br/>
All done!
</p>
