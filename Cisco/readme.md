# Cisco

First of all, the one who is writing this readme and giving you general ideas
about Cisco has done nothing about network and routing. I, however, have done a
lot of research about Cisco and I am capable of at least, writing about some
general guidelines to get you started.

## What is Cisco?

Cisco is a company that makes networking equipment, such as routers, switches,
and firewalls.

<div style="text-align: center">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Cisco_logo_blue_2016.svg" aria-label="Logo of Cisco">
</div>

## Why Study Cisco?

Cisco is not a very important part of CyberPatriot, at least, for the first two
rounds (30 points out of 330). However,  we must not consider the use of such
technology just as in CyberPatriot. The network itself is a very important part of
the CyberPatriot, as well as major companies and organizations. Therefore, it is
important to learn about Cisco.

If you are not convinced, ask yourself:

- What's the difference between Bridged, Nat, and Host-only in VMWare Workstation?
- When you import a socket and do some networking in Java/Python, what happens?

```java
Socket socket = new Socket("google.com", 80);
socket.getOutputStream().write("GET / HTTP/1.1\r\nHost: google.com\r\n\r\n".getBytes());
socket.getOutputStream().flush();
System.out.println(new String(socket.getInputStream().readAllBytes()));
```

- And most importantly, if your computer is down (or any connection between two
  computers is down), how do you troubleshoot?

We must appreciate the vast beautiness of abstraction, that we can do all of these
without knowing the details of how the network works. However, we must know the
details of how the network works, to be able to do anything better.

You should consider the study of Cisco as a mixture of your journey at AP World
History/AP European History and AP Computer Science A. You will learn a lot of theory
as well as do some coding.

## How to Study Cisco?

### Learn the basics of the Internet

- We won't start with Cisco administration. A general idea of the Internet and
  its protocols is desirable before we start.
  > However, if you are urgent to start (and or competition is approaching
  > <del>and you prastinate till now</del>), you can skip this part.
- Regardless of whether you had studied AP CSP or not, I strongly recommend you
  don't skip this section. Simply put, the network taught in AP CSP is not
  enough.
- A sample of questions that you should be able to answer after that stage.
  Notice this is not comprehensive.
  - Distinguish between Port, IP, and MAC address as well as their
    functionality.
    - ARP, RARP, and GARP
    - DHCP
    - Subnet, subnet mask, and CIDR notation.
  - Distinguish between TCP and UDP as well as their functionality.
    - When to use TCP and UDP? For example, when a chat application uses
      UDP, what is the reason?
  - 2- and 3-layer switching
    - Switch
    - Router.
    - What's the difference between a Router and a Switch?
    - Your teacher taught you the broadcast domain and collision domain,
      what's the difference?
    - Does the usage of a switch reduce collision, or increase
      collision/broadcast domains?
  - What is the OSI model? What are the layers? What are the protocols in
    each layer?
- Read the following books and/or follow those tutorials. PDFs are available
  in this repo as well.
  - [Crash Course of Computer Science](https://www.youtube.com/watch?v=3QhU9jd03a0) has 28# and 29#
    episodes.
  - [Computer Networking: A Top-Down
    Approach](https://www.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149)
  - (Chinese Warning) [趣谈网络协议](https://book.douban.com/subject/35013753/)

### Learn Cisco

- The above parts are just theories. Just knowing them, are still far from what we
  need to do in the competition. We need to know how to use Cisco.
- Here is the fun part, where we will type commands in the terminal. However,
  this doesn't mean we need to buy everyone some expensive Cisco routers and
  switches. We can use:
  - [GNS3](https://www.gns3.com/), a network simulator. Notice Hyper-V and/or
    VMWare Workstation are needed to install Cisco images. It also supports the
    emulation of Cisco IOS only (which lacks some features).

  - [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer), a
    network simulator. Notice it is only available for students. Credentials
    are available when in contact with your team leader/teacher. It only supports
    emulation, i.e., finite subsets of command of Cisco IOS are available,
    and some configurations are not available at all.

    **Use that for the competition.**
- Read the following books and/or follow those tutorials. PDFs are available in
  this repo as well:
  - [FREE CCNA 200-301 // Complete Course // NetworkChuck
    2021](https://www.youtube.com/playlist?list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P)
    Theory and practice are taught altogether.
  - *An Introduction to Networks and Cisco – Beginners Course* A book written by
    past CyberPatriot competitors that contained 144 pages.
  - *Cisco CCNA in 60 Days*. An 808-page book that comes with some explanation
    of concepts (skim through with assumption of previous knowledge), extensive
    Cisco theories and commands, and some practice questions & lab.
## What's next?

- *Routing TCP/IP, Volume I: Foundation of IP* & *Routing TCP/IP, Volume II:
  CCIE Professional Development* by Jeff Doyle. A 1000-page book that contains a
  lot of theory and practice. It is a bit outdated but still useful.

# Reference/Cheat Sheet

- *Cisco Cheat Sheets*. A huge collection of pdfs from Cisco Netacad and [Packet
  Life](https://packetlife.net/). All sections are named and aligned to their
  content, by the courtesy of [@anishgoyal1108](https://www.github.com/anishgoyal1108)
  - Those cheat sheets describe the concepts in concise graphs and tables. They
    further described appropriate commands in the following pages.
- In `commands` directory
  - *Packet Tracer Scripting Guide*. Consider this as some helper function
    defined for Cisco in PDF. It is not an exhaustive list of commands, however,
    a cookbook of common tasks.
  - *All Cisco Command* (7 pages 12 pt font), *CCNA Commands Summary* (35 pages
    16 pt font), and *Essential Cisco IOS Commands Summary* (12 pages 14 pt
    font). A list of all commands in Cisco IOS. PDF version of *All Cisco
    Command* is compiled as Word may not be available inside the VM.
- In `userguides` directory
  - This is a directory of Cisco User Guides from 2010.
  - *Cisco IOS Configuration Fundamentals Command Reference*
  - *Cisco Network Modules Hardware Installation Guide*
  - *Network Processing Engine and Network Services Engine Installation and Configuration*
