# CamHack
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![cheese](https://1.bp.blogspot.com/-qfrM2I6_SNs/W2Z-mnVJPdI/AAAAAAAAAD0/LSEYXNbzBjAf-7R7hPg7Z2jo0uTIKRtMgCPcBGAYYCw/s1600/1530090346322.jpg)

# What is CamHack?
<p>CamHack is a Tool to take cam shots of target's phone fornt camera or PC webcam. CamHack Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Perrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/tvp620/CamHack
cd CamHack
bash camhack.sh
```
### Video Demo
[![How to control android camera](https://img.youtube.com/vi/G_nNHrWwCOM/0.jpg)](https://www.youtube.com/watch?v=G_nNHrWwCOM)
#### For More Video subcribe <a href="https://www.youtube.com/channel/UCyQ-X0cNy9YcmeHNwouxNbw">Technical Vivek Pathak YouTube Channel</a>
<p>CamHack is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
<p>CamHack is inspired by https://github.com/thelinuxchoice/ Big thanks to @thelinuxchoice</p>
