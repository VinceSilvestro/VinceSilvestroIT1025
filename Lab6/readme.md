# Executive Summary

This lab focuses on the protocols that support communication on the internet such as IP, TCP/IP, HTTP, and HTTPS. Another objective of this lab was to create a practice web page using HTML and CSS. 

---

# Internet Architecture 

### Internet Protocol 

An Internet Protocol, or IP address is a set of unique identifying numbers found on every individual device connected to the internet. IPv4, the original standard, had four numbers with values ranging from 0 to 255 separated by periods. After these numbers became unusable, IPv6 started becoming the norm. IPv6 has eight groups of four hexadecimal digits and uses colons instead of decimal points. 

The Internet Corporation for Assigned Names and Numbers, or ICANN is a not-for-profit public-benefit corporation that maintains databases of namespace and numeral spaces on the internet. ICANN administers and coordinates IP addresses worldwide, following their mission of “ensur[ing] a stable and unified global internet.” 

### TCP/IP

TCP/IP is also known as Transmission Control Protocol/Internet Protocol. Like its name suggests, it is a protocol that is used to synchronize two internet devices using appropriate virtual ports. Like the transmission of a car, TCP/IP “shifts gears,” so to speak, into a channel that the two devices can agree upon. Each IP address can open and communicate over up to 65535 different ports. 

One way to imagine TCP/IP is in terms of the client-server model. The device requesting service in a two-way online interaction would be the client and the device providing service would be the server. In reality, both parties would be providing information to each other, but the client would merely initiate the interaction. 

Layered protocol stacks are important to changing technology because individual layers of networking protocol can be changed without affecting other layers. 

The types of applications that run on the application layer are protocols such as HTTP, FTP, POP3, SMTP, and SNMP.

### Internet Security

HTTP is Hypertext Transfer Protocol. It is the protocol used for viewing web pages online. All information used in this method is sent in clear text. Devices browsing the web send information to web servers over the public internet, thus supporting the client-server model.

HTTPS is like HTTP, except secure. HTTPS uses encryption algorithms to scramble the data that is being retrieved by HTTP, making it impossible to read by unauthorized viewers. One protocol that HTTPS uses to protect data is Secure Sockets Layer, or SSL, which uses public key encryption to secure data. The web browser requests certification from the web server, which then sends an SSL certificate to authenticate the identity of a website. The other protocol that HTTPS uses is Transport Layer Security, or TLS. TLS is the successor to SSL and shares the same mechanisms that SSL does, with the addition of authenticating both the client and the server in the online interaction. 

### Securing your Web Browser

Securing your web browser is important because many browsers are configured to provide increased functionality at the cost of decreased security out of the box. Keeping browsers in an insecure configuration can introduce vulnerabilities to internet devices. These weaknesses can lead to damaged software, hardware, and compromised personal information. 

One risk associated with web browsers is the use of cookies. Cookies are small files that temporarily store user preferences on a local machine, usually via web browsers. Large corporations like Facebook, Google, and Twitter can use cookies to follow us around the web and collect data about our internet usage. This can be especially damaging if these sort of companies sell our data to other merchants, making our personal information vulnerable to attackers. 

---

# Internet Programming

### World Wide Web Consortium

Tim Berners-Lee is the inventor of the World Wide Web. He founded the World Wide Web Consortium, or W3C, in 2009 to coordinate efforts to further the potential of the Web to benefit humanity. 

W3C standards define an Open Web Platform for application development and pertain to Web Design and Applications, Semantic Web, XML Technology, and more. Another area that W3C applies specifications and guidelines to is Web Architecture. Standards for Web Architecture are important because they focus on the foundation technologies that keep the web running smoothly, like URIs and HTTP.

### HTML5 and CSS

HTML5 is the latest version of the Hyper Text Markup Language. HTML is the standard markup language for creating web pages. CSS, Cascading Style Sheets, is a style sheet language used to describe the appearance of web pages within HTML. To create my fictitious band’s website, I used a public Google Drive bit of code to pull an image saved in my Google Drive and push it onto the web page. First, I made all of the social media icons “public on the web” as it is in Google Drive. Then, I copied the file’s ID which is found in the Google Drive shareable link. I then pasted that ID after the equals sign in this partial link: https://drive.google.com/uc?id=. Although the images do not appear at the time of this lab submission, the alternate text describes the logo instead. 

### HTML and XML

XML differs from HTML in that XML was designed to carry data, similar to Notepad on Windows, while HTML primary focuses on how the data actually looks; HTML has predefined tags and XML does not. 

---

# Components of a URL

In URLs, https, http, and so forth, are types of schemes. www.amazon.com and vincesilvestro.com, for example, are the domains. The “.edu” or “.com” portion of a domain is considered the top-level domain. In the following URL, https://www.youtube.com/watch?v=OvF_pnJ6zrY&ab_channel=Techquickie, this information would be the parameters: “?v=OvF_pnJ6zrY&ab_channel=Techquickie.” If “/en/internet-tips/understanding-urls/1/ is not added to the end of https://edu.gcfglobal.org/en/internet-tips/understanding-urls/1/ then the default page, https://edu.gcfglobal.org will be brought up. An anchor will tell a browser to load a specific part of the page, usually a certain heading in an article. For example, #Discography communicates to Google Chrome, Safari, and so forth, to scroll down to 
George Harrison’s discography in his Wikipedia article (https://en.wikipedia.org/wiki/George_Harrison#Discography). 

---

# Conclusion 

The internet is an extremely vast space of protocols working together to create one smooth, seamless user experience. To me, understanding protocols such as IP, TCP/IP, HTTP, and HTTPS further cement this idea. Personally, I enjoyed creating my practice site but struggled to make the images appear my preferred size. I also hope to explore other HTML applications that may correct these issues in the future. 
