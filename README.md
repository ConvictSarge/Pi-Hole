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

Immediatly ran update && upgrade

Ran the wget command from pi-hole.net

It's working... set my laptop to the DNS of pi-hole

Set my router interface to the DNS of pi-hole 

All done!

I think my next tinker will be a wireguard tunnel for my PIA account...
