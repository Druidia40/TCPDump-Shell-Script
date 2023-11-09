<h1>Analyze Network Traffic with TCPDump</h1>
<h2>Description</h2>
This lab uses one of the most versatile Linux networking utilities tcpdump to capture and analyze TCP traffic. This lab will review how tcpdump works, how to apply filters when capturing TCP packets and how to analyze the packets that were captured.
<br/>
<br />

<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 

<h2>Environments Used </h2>

- <b> Visual Studio Code and Wireshark</b>

<h3>Applying filters to tcpdump commands:</h3>

<p align="left">
Basic command to capture 10 packets 
<br/>
<img src="https://i.imgur.com/caMzVP6.png" height="60%" width="60%" alt="TCP Screenshot"/>
<br /> 
  
Capturing 10 packets and viewing it in ASCII format 
<br/>
<img src="https://i.imgur.com/rihnZqa.png" height="60%" width="60%" alt="ASCII Screenshot"/>
<br />

Command line to list all interfaces
<br />
<img src="https://i.imgur.com/KJPn0kw.png" height="60%" width="60%" alt="Interfaces Screenshot"/>
<br />

Capturing 10 packets from a specific interface
<br/>
<img src="https://i.imgur.com/McYIK36.png" height="60%" width="60%" alt="Packets list from a single interface snapshot"/>
<br />

Capturing 10 packets from a host in -#tttt format
<br/>
<img src="https://i.imgur.com/G7094H1.png" height="60%" width="60%" alt="tttt snapshot"/>
</p>

<h2> Summary </h2>
I used the tcpdump command to pull TCP packets. I filtered these packets in different formats to gather different views. I also used the -D command to view the different interfaces that I can capture data from. Finally, I ran a tcpdump command to collect 10 packets from a host site.
