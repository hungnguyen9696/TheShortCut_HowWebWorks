## Web - Basic Concepts

#### What is Internet?

The Internet is essentially a global network of computing resources. You can think of the Internet as a physical collection of routers and circuits as a set of shared resources.

Some common definitions

A network of networks based on the TCP/IP communications protocol.
A community of people who use and develop those networks.

#### Internet-Based Services

Some of the basic services available to Internet users are:

- Email − A fast, easy, and inexpensive way to communicate with other Internet users around the world.

- Telnet − Allows a user to log into a remote computer as though it were a local system.

- FTP − Allows a user to transfer virtually every kind of file that can be stored on a computer from one Internet-connected computer to another.

- UseNet news − A distributed bulletin board that offers a combination news and discussion service on thousands of topics.

- World Wide Web (WWW) − A hypertext interface to Internet information resources.

#### What is WWW?

WWW stands for World Wide Web. A technical definition of the World Wide Web is − All the resources and users on the Internet that are using the Hypertext Transfer Protocol (HTTP).

A broader definition comes from the organization that Web inventor Tim Berners-Lee helped found, the World Wide Web Consortium (W3C): The World Wide Web is the universe of network-accessible information, an embodiment of human knowledge.

In simple terms, The World Wide Web is a way of exchanging information between computers on the Internet, tying them together into a vast collection of interactive multimedia resources.

#### What is HTTP?

HTTP stands for Hypertext Transfer Protocol. This is the protocol being used to transfer hypertext documents that makes the World Wide Web possible.

A standard web address such as Yahoo.com is called a URL and here the prefix http indicates its protocol

#### What is URL?

URL stands for Uniform Resource Locator, and is used to specify addresses on the World Wide Web. A URL is the fundamental network identification for any resource connected to the web (e.g., hypertext pages, images, and sound files).

A URL will have the following format −

```
protocol://hostname/other_information
```

The protocol specifies how information is transferred from a link. The protocol used for web resources is HyperText Transfer Protocol (HTTP). Other protocols compatible with most web browsers include FTP, telnet, newsgroups, and Gopher.

The protocol is followed by a colon, two slashes, and then the domain name. The domain name is the computer on which the resource is located.

Links to particular files or subdirectories may be further specified after the domain name. The directory names are separated by single forward slashes.

#### What is Website?

A collection of various pages written in HTML markup language.

Each page available on the website is called a web page and first page of any website is called home page for that site.

#### What is Web Server?

Every Website sits on a computer known as a Web server. This server is always connected to the internet. Every Web server that is connected to the Internet is given a unique address made up of a series of four numbers between 0 and 256 separated by periods. For example, 68.178.157.132 or 68.122.35.127.

When you register a Web address, also known as a domain name, such as github.com you have to specify the IP address of the Web server that will host the site.

#### What is Web Browser?

Web Browsers are software installed on your PC. To access the Web you need a web browsers, such as Google Chrome, Microsoft Internet Explorer or Mozilla Firefox.

Currently you must be using any sort of Web browser while you are navigating through my site github.com. On the Web, when you navigate through pages of information this is commonly known as browsing or surfing.

#### What is SMTP Server?

SMTP stands for Simple Mail Transfer Protocol Server. This server takes care of delivering emails from one server to another server. When you send an email to an email address, it is delivered to its recipient by a SMTP Server.

#### What is ISP?

ISP stands for Internet Service Provider. They are the companies who provide you service in terms of internet connection to connect to the internet.

You will buy space on a Web Server from any Internet Service Provider. This space will be used to host your Website.

#### What is HTML?

HTML stands for Hyper Text Markup Language. This is the language in which we write web pages for any Website. Even the page you are reading right now is written in HTML.

This is a subset of Standard Generalized Mark-Up Language (SGML) for electronic publishing, the specific standard used for the World Wide Web.

#### What is Hyperlink?

A hyperlink or simply a link is a selectable element in an electronic document that serves as an access point to other electronic resources. Typically, you click the hyperlink to access the linked resource. Familiar hyperlinks include buttons, icons, image maps, and clickable text links.

#### What is DNS?

DNS stands for Domain Name System. When someone types in your domain name, www.example.com, your browser will ask the Domain Name System to find the IP that hosts your site. When you register your domain name, your IP address should be put in a DNS along with your domain name. Without doing it your domain name will not be functioning properly.

#### What is W3C?

W3C stands for World Wide Web Consortium which is an international consortium of companies involved with the Internet and the Web.

The W3C was founded in 1994 by Tim Berners-Lee, the original architect of the World Wide Web. The organization's purpose is to develop open standards so that the Web evolves in a single direction rather than being splintered among competing factions. The W3C is the chief standards body for HTTP and HTML.

## Web - How it Works ?

On the simplest level, the Web physically consists of the following components:

- Your personal computer − This is the PC at which you sit to see the web.

- A Web browser − A software installed on your PC which helps you to browse the Web.

- An internet connection − This is provided by an ISP and connects you to the internet to reach to any Website.

- A Web server − This is the computer on which a website is hosted.

- Routers & Switches − They are the combination of software and hardware who take your request and pass to appropriate Web server.

The Web is known as a client-server system. Your computer is the client and the remote computers that store electronic files are the servers.

#### How the Web Works

When you enter something like Google.com the request goes to one of many special computers on the Internet known as Domain Name Servers (DNS). All these requests are routed through various routers and switches. The domain name servers keep tables of machine names and their IP addresses, so when you type in Google.com it gets translated into a number, which identifies the computers that serve the Google Website to you.

When you want to view any page on the Web, you must initiate the activity by requesting a page using your browser. The browser asks a domain name server to translate the domain name you requested into an IP address. The browser then sends a request to that server for the page you want, using a standard called Hypertext Transfer Protocol or HTTP.

The server should constantly be connected to the Internet, ready to serve pages to visitors. When it receives a request, it looks for the requested document and returns it to the Web browser. When a request is made, the server usually logs the client's IP address, the document requested, and the date and time it was requested. This information varies server to server.

An average Web page actually requires the Web browser to request more than one file from the Web server and not just the HTML / XHTML page, but also any images, style sheets, and other resources used in the web page. Each of these files including the main page needs a URL to identify each item. Then each item is sent by the Web server to the Web browser and Web browser collects all this information and displays them in the form of Web page.

#### In Short

We have seen how a Web client - server interaction happens. We can summarize these steps as follows:

- A user enters a URL into a browser (for example, Google.com. This request is passed to a domain name server.

- The domain name server returns an IP address for the server that hosts the Website (for example, 68.178.157.132).

- The browser requests the page from the Web server using the IP address specified by the domain name server.

- The Web server returns the page to the IP address specified by the browser requesting the page. The page may also contain links to other files on the same server, such as images, which the browser will also request.

- The browser collects all the information and displays to your computer in the form of Web page.
