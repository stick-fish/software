# software
Bare minimum for a new VM Installation

<h3>Screenshots</h3>
https://github.com/GNOME/gnome-screenshot
<ul>
  <li>GNOME Screenshot (for GNOME desktop users)</li>
  <li> Runs on Kali, Kubuntu KDE, Mint 19 XFCE without problems </li>
  <li><code>sudo apt install gnome-screenshot</code></li>
  <li>Create shortcut in the shortcut area of distro </li>
  <li>Assign command:</li>
  <li><code>gnome-screenshot -a</code></li>
  <li>User selected area for screenshot, not whole screen </li>
  <li>Hot keys I use: <code>ctrl + alt + p</code></li>
 </ul>

<h3>NFSShell</h3>
https://pentestacademy.wordpress.com/2017/09/20/nfs/
<ul>
  <li><code>apt-get install libreadline-dev libncurses5-dev</code></li>
  <li><code>make</code></li>
  <li><code>gcc -g -o nfsshell mount_clnt.o mount_xdr.o nfs_prot_clnt.o nfs_prot_xdr.o nfsshell.o -L/usr/local/lib -lreadline -lhistory -lncurses</code></li>
  <li><code>./nfsshell</code></li>
</ul>

<h3>Python FTP Server</h3>
https://github.com/giampaolo/pyftpdlib
<code>sudo apt install pyftpdlib</code>

<h3>Cherry Tree</h3>
https://www.giuspen.com/cherrytree/
<code>sudo add-apt-repository ppa:giuspen/ppa</code>
<code>sudo apt-get update</code>
<code>sudo apt install cherrytree</code>

<h3>enum4linux fix & nmap smb scripts</h3>
Found this online to fix some of the errors during pwk:
<code>edit:- /etc/samba/smb.conf in the [global] section:</code>
<code>client min protocol = SMB2</code>
<code>client max protocol = SMB3</code>

