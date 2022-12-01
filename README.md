# Frontend Roadmap and Notes

## Roadmap - https://roadmap.sh/frontend

### Internet
The internet is decentralized, which means that no one owns the internet or controls who connects to it. Different organizations have their own network and voluntarily negotiate interconnection agreements.

Web is not the whole internet but the most popular application of the internet. Other applications include Email and BitTorrent.

3 Parts:
* Last Mile - The part which connects home and small businesses to the internet. Connections provided by cable TV companies, new fibre optic connections or the old DSL service providers over telephone cable. Also includes towers for mobile data.
* 

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
