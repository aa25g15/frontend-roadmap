# Frontend Roadmap and Notes

## Roadmap - https://roadmap.sh/frontend

### The internet, Explained - https://www.vox.com/2014/6/16/18076282/the-internet
The internet is decentralized, which means that no one owns the internet or controls who connects to it. Different organizations have their own network and voluntarily negotiate interconnection agreements.

Web is not the whole internet but the most popular application of the internet. Other applications include Email and BitTorrent.

Uses TCP/IP protocol.

#### 3 Parts:
* Last Mile - The part which connects home and small businesses to the internet. Connections provided by cable TV companies, new fibre optic connections or the old DSL service providers over telephone cable. Also includes towers for mobile data.
* Data Centers - Large rooms full of servers which host apps and content. Usually owned and operated by large corporations such as Google and Meta. Usually build in remote locations. Very fast internet connections allowing them to serve multiple users simultaneously.
* Backbone - This is what connects data centers to last mile users. Usually long fibre optic cables. Backbone providers usually connect their networks together at Internet Exchange Points (IEPs).

#### Who runs the internet?
* No one in particular but there are some key organizations
* The shared technical standards that make the internet work are managed by an organization called the Internet Engineering Task Force.
* The Internet Corporation for Assigned Names and Numbers (ICANN) is sometimes described as being responsible for internet governance. As its name implies, ICANN is in charge of distributing domain names (like vox.com) and IP addresses. 

#### What’s an IP address?
A unique number that identifies a computer on the internet. Eg - IP address for vox.com is 216.146.46.10.

#### What is IPv6?
IPv4 allows for 4 billion unique IP addresses but this limit is running out! IPv6 has 39 digits to ensure that world will never run out again.

#### How does wireless internet work?
2 types:
* Wifi - Anyone can purchase wifi equipment. Strictly low power and low range. Uses unlicensed frequencies which are free for use.
* Cellular - Areas are divided into cells. Denser areas have smaller cells such as a city block, in rural areas, cells can be miles long. Each cell has a tower in the center to provide connectivity. When a user goes from one cell to another, the tower automatically hands over the device to the next tower providing seamless connectivity. Cellular networks use licensed frequencies, as they are scarce, they are usually auctioned.

#### What is the cloud?
Allows consumers to treat internet as a utility, leaving technical details to tech companies. Such as hosting files on the internet which are avaliable everywhere and automatically synced and SAAS products such as Google Docs. Unlike old MS Word, people do not have to manage files locally, do not have worry about version changes and do not have to worry about installing new updates.

Earlier companies had to purchase their own servers to host a website. Now with AWS and the likes, companies can rent servers buy the hour. It has lowered the barrier to entry for creating websites.

#### What is a packet?
* Basic unit of information sent over the internet.
* Has a header containing packet length, source, destination and checksum to validate if the package was damaged during transit.
* Then has the actual data which could be up to 64 kbs or roughly 20 pages of plain text.
* If internet routers experience congestion or technical problems they can just discard packets. It is the responsibility of the sender to resend the packet which has failed to reach its destination.

#### What is the World Wide Web?
It is the most popular way of publishing information on the internet. Has hyperlinks to easily navigate between pages. Created by Tim Berners Lee. W3C consortium maintains standards but cannot enforce them. In actual, Microsoft, Google, Apple, Mozilla control the internet. The standards they adopt become the standards for the web.

#### What’s a web browser?
A web browser is a computer program that allows users to download and view websites.

#### What is SSL?
SSL is short for Secure Sockets Layer which is a family of encryption technologies which make the communication between the client and server secure. Under the hood, SSL accomplishes that by transforming your data into a coded message that only the recipient knows how to decipher. If a malicious party is listening to the conversation, it will only see a seemingly random string of characters, not the contents of your emails, Facebook posts, credit card numbers, or other private information. Websites using SSL have a lock in the search bar next to the URL.

#### What is the Domain Name System?
The DNS is the reason why we can access Vox by typing vox.com instead of a hard to remember numeric address. The system is hierarchical. Eg - .com is managed by a company called Verisign. It assigned names such as google.com and so on. The owners of these domain names can further define sub-domains such as mail.google.com and so on.

#### Who decides what domain names exist and who gets them?
DNS is managed by ICANN which is a non-profit. 

2 types of domain names:
* gTLDs (generic top-level domains) - .com, .org, .edu etc.
* ccTLDs (country-code top-level domains) - .in, .uk, .io, .us

### What is a Server? - https://www.techtarget.com/whatis/definition/server
A program that "serves" requests in the literal sense of the word. Physical server is a system running an OS and a program to serve requests. But it is more common and advantageous to run multiple virtual servers which are utilising common hardware. A virtual server is independent of other servers using the same hardware and has its own OS and applications. The IP address and full qualified domain name are supplied at the OS level.

You personal PC can work as a development server but it is not adequately designed to be a production server. Production servers have lots of fail-safe mechanisms.

#### Types of servers:
Servers are often categorized in terms of their purpose. A few examples of the types of servers available are as follows:
* Web server: A computer program that serves requested HTML pages or files. In this case, a web browser acts as the client.
* Application server: A program in a computer in a distributed network that provides the business logic for an application program.
* Proxy server: Software that acts as an intermediary between an endpoint device, such as a computer, and another server from which a user or client is requesting a service.
* Mail server: An application that receives incoming emails from local users -- people within the same domain -- and remote senders and forwards outgoing emails for delivery.
* Virtual server: A program running on a shared server that is configured in such a way that it seems to each user that they have complete control of a server.
* File server: A computer responsible for the central storage and management of data files so that other computers on the same network can access them.
* Database server: this server is responsible for hosting one or more databases. Client applications perform database queries that retrieve data from or write data to the database that is hosted on the server.

#### Server Components:
* Hardware - Typically a rack mount chassis containing power supply, a system board, one or more CPUs, memory, storage and a network interface. Hardware also commonly supports out-of-band management through a dedicated network port. It allows low-level management and monitoring of the server independent of the OS.
* OS - A server OS such as Windows Server or Linux. OS provides applications access to hardware resources that they need and provide network connectivity. Applications are what enable a server to do its job. Eg - A mail server would run a mail application, a DB server would run a DB application.
