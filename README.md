# DNS
so,what is DNS

D - DOMAIN

N - NAME

S - SYSTEM

DNS is a system of converting human redable websites like google.com into thier respective ip addresses like 192.168..... it is like a conatct book for everyname thier is a unique phone nuber same goes for this for everywebsite thier exist a ip addresss its the the user ip (ex you device ip dont resemble it is server which is also a device on which website is hosted this ip is of server althogh user ip is used to esablish connection between web browser and server when your browser connecte with that server
# how DNS works behind the scenes
# DNS Recursor
The DNS recursor is the first place your request goes when you type a website address in your browser. Think of it like a helper (a server, which is a physical machine) that receives your request to find the website. The DNS recursor's job is to do the work of figuring out which IP address is linked to the website you’re trying to visit. If it doesn't know the answer, it will ask other servers to help find it.

# Root Nameserver
After the recursor gets your request, it sends it to the root nameserver. The root nameserver acts like the table of contents in a book. It knows where to start looking and tells the recursor which "section" to go to next. In this case, it directs the recursor to the right TLD nameserver based on the ending part of the website (like `.com`, `.org`, etc.).

# TLD Nameserver
The TLD nameserver is like a specific shelf in a library. It handles the last part of the website name, such as `.com`, `.org`, or `.net`. For example, if the website is `example.com`, the TLD server is responsible for `.com`. It helps narrow down the search by pointing the recursor to the correct authoritative nameserver, which has the detailed information about the website.

# Authoritative Nameserver
The authoritative nameserver is the final step. It’s like a dictionary on the shelf that contains the exact definition. This server holds the actual information about the website you're trying to reach, including its IP address. If it has the data, it will return the correct IP address to the DNS recursor, which then passes that information back to your browser so the website can load.




------- Going on
