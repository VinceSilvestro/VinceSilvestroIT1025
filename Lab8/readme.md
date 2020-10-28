# Executive Summary

This lab details the way that data is organized, manipulated, and protected. As technology becomes increasingly more accessible, data is being generated at higher and higher volumes. Regulations that protect user privacy are becoming steadily more necessary as we become more introspective to our online culture as a society. 

---

# Data, Information and Knowledge

### Relational Data

Although often used interchangeably, data, information and knowledge have their open unique meanings. Data can be thought of as the raw facts and figures that describe something. Information necessitates a useful collection of data, such as statistics over a period of time. Knowledge requires information to make assumptions that offer real world consequences and insight. 

In a database of two tables—customers and orders—the primary key for customers could be a unique customer identification number. For orders, the primary key could be an order number. 

These two tables would be related in that the orders table would display a customer ID row, for each order placed, as with the customer table. 

In the orders table, the foreign key would be customer ID. 

In a situation where the orders table had a date field, it would be important to properly define the data as a “Date/Time” numeric data type as opposed to one with text string, for example. This is because the data type tells the database what set of functions are allowed to be performed. Another reason for assigning data types is to permit the appropriate amount of storage space for the data. 

### Big Data

Big data is defined by data with the presence of the four V’s, which are volume, variety, veracity and velocity. Volume refers to data in a mass quantity. Variety points to data of numerous types, falling into categories or otherwise uncategorized. Veracity in big data represents the precision in the data-collecting process resulting in quality, trustworthy data points. The final V, velocity, is generally the rapid speed at which data is created and collected over the internet. 

The internet has driven the increased need for big data analysis and processing. Specifically, smartphone cameras, microphones, GPS sensors, accelerometer data, Internet of things devices (like motor vehicles, thermostats and other smart appliances), social media sites and browsing/search history, to name a few, have all contributed to this necessity. 

---

# Structured Query Language (SQL) Injections

SQL is a standard language for accessing and manipulating databases. RDBMS, or the Relational Database Management System, stores data in database objects called tables. RDBMS is the basis for most modern database systems, such as Oracle, which utilize the SQL format. 

In the Northwind Traders practice database saved in this lab folder, two tables of interest to me are Products and Suppliers. The primary keys for Products and Suppliers are ProductID and SupplierID, respectively. The foreign key for Products is SupplierID. This means that users can navigate to the supplier of any product in the Products table via the SupplierID. 

SQL injections are when hackers insert harmful code into SQL statements. They can cause serious security threats and even potentially destroy a database. Hackers with malicious intent can find ways to obtain all usernames and passwords in a database, alter every other type of field, and even delete precious data, for example. To reduce these sorts of issues, programmers can equip their websites with SQL parameters. SQL parameters are values manually added to an SQL query, often simply “@” symbols. For instance, the “@” symbols are usually placed in front of numbers 0, 1, and 2 to prevent hackers from injecting code like 0=0. Although seemingly harmless, 1=1, 2=2, and so forth will always be true and display any desired data unless programmers take precautions. 

---

# Ethical and Legal Implications

### Code of Ethics

The purpose of a code of ethics in an organization is to communicate the common workplace guidelines to everyone simply and clearly. The ACM, or Association for Computing Machinery, created a code for the computing discipline to detail specific ethical questions that go beyond admonitions such as “always acting with integrity” and “always being truthful with the team.”

A code of ethics and an AUP, or acceptable use policy, are similar to each other because they both lay out acceptable and unacceptable actions in an organization. They are different in the sense that AUPs are often agreements that users need to make in order to use services like WiFi. A code of ethics almost always denotes preferred behaviors in a professional setting. 

Google, for example, has an AUP for their Cloud Platform (https://cloud.google.com/terms/aup). Google Cloud Platform offers a wide variety of development, data storage, and managerial tools for businesses. It also includes Google Workspace (G Suite) products such as Gmail, Google Drive, and Google Calendar. I found its AUP to be broad-ranging and unspecific. My main takeaway from reading the policy was that the Google customer agrees to not use their products to break the law. They highlighted violating the Digital Millennium Copyright Act, distributing viruses, and interfering with Google service operations in general; accessed in October 2020 and last modified in 2015, there were no consequences or disciplinary actions to be found on this page. 

### Intellectual Property

The World Intellectual Property Organization, or WIPO, is the “global forum for intellectual property (IP) services, policy, information and cooperation,” according to their own website. Their mission is to lead the development of an international intellectual property system that facilitates innovation and creativity for the benefit of humanity. 

Copyright is the protection of authors for their creative works. It is the legal right to do whatever a creator might want to do with it. By actually just bringing an original work into existence, an author automatically has the copyright to that creation. Since a registered copyright is needed to take someone to court over an artistic dispute, registering for a copyright is beneficial to those using their work in commercial settings. With this being said, if someone tried to steal the logo for my delivery service concept (from Lab 4), I would be unable to take legal action against this person if the svg image was not a registered copyright.  

If the image I created became an item that identifies my business, a trademark would primarily be a means to protect consumers who might use it. It would create a distinction and eliminate confusion among my company and any other company that is similar or completely different. 

### Information Collection

Personally identifiable information is being collected about internet users all of the time. Information like social network data, online purchases, browser history, phone records, and biometric data is bought and sold to companies in the form of profiles, often without explicit consent from the user. US guidelines like COPPA, FERPA, and HIPAA work to protect people’s privacy and restrict the collection of information online. The Children’s Online Privacy Protection Act requires websites to make an effort to determine the age of its users, and demands parental consent to collect information if they are under thirteen years old. The Family Educational Rights and Privacy Act mainly aims to protect student education records. Under this law, parents have the right to their child’s school records until the child turns eighteen or begins post-secondary education, when the student is then given these exclusive rights. The Health Insurance Portability and Accountability Act of 1996 puts medical records in a special category of personally identifiable information and gives patients complete control over such records.  

---

# Conclusion

This lab explored data, information and knowledge topics such as relational data and big data in the form of databases; SQL; SQL injections and hacking; and finally the ethical and legal implications of data collection, involving codes of ethics, intellectual property, and information collection. 


