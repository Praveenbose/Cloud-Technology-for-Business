# Cloud-Technology-for-Business- B9MG119



## 1. Primary Objective

The primary objective of this project is to develop a comprehensive cloud strategy for BookShow, the leading online ticketing platform based in india. BookShow currently manages its own IT infrastructure, including hardware, software and on-site. Our strategy aims to transition the company’s current on-premises model to a cloud-based solution that will enhance operational efficiency and overall business performance. To help drive this transformation, we will outline a detailed cloud strategy and a sample deployment plan.
2. Background of the Enterprise
BookShow is a prominent entertainment company known for its leading Online Ticketing Platform, catering to a wide array of events including movies, plays, concerts, and sporting events. In addition to ticketing, BookShow offers an online media streaming service and comprehensive management solutions for both virtual and on-ground entertainment experiences, covering all genres. The core operation of BookShow revolves around its online platform, which facilitates the booking of tickets for various entertainment events, with a primary focus on movies. 
2.1 Size of the Business

BookShow is a medium-sized enterprise with a total of approximately 33 employees. The workforce is structured as follows:

IT Management:
  - 2 IT Managers

Network and Systems Administration:
  - 2 Network Administrators
  - 4 Systems Administrators

Development Team:
  - 4 Backend Developers
  - 4 Frontend Developers

IT Support and Maintenance:
  - 3 IT Support Specialists
  - 4 Help Desk Technicians

Cloud and Database Management:
  - 1 Cloud Engineer
  - 2 Cloud Solutions Architects
  - 2 Database Administrators

Project and Security Management:
  - 1 Scrum Master
  - 3 Security Specialists
  - 1 IT Project Manager

Let's delve into the detailed IT infrastructure of BookShow, covering aspects of hardware, software, and on-site management.
3. Current IT setup 

3.1 Hardware
 
On-premises Servers:

BookShow’s IT infrastructure includes several key components. The web servers host the website and application, handling user inquiries, ticket bookings, and providing web content, typically using software like Apache and Nginx (Nginx, n.d.; Apache HTTP Server Project, n.d.). The database servers are dedicated to storing and managing transactional data, customer information, and event details, utilizing relational database management systems like SQL Server or PostgreSQL (Microsoft SQL Server, n.d.; PostgreSQL, n.d.). Media servers are employed for streaming media content and storing large media files. Backup servers ensure critical data backup and data availability during power outages. In addition to other features, hardware load balancers are utilized to ensure that web traffic is evenly distributed to web servers, resulting in high availability and reliability.

3.2 Software

Operating Systems:

The operating systems primarily used are Linux servers, such as Ubuntu and CentOS, chosen for their reliability and security, and deployed across web, database, and media servers. BookShow utilizes several key applications and services to ensure smooth operations. A custom ticketing platform is  specialized software that manages ticket bookings, user profiles, financial transactions, and event organization. CRM (Customer Relationship Management) will manage interactions with customers, sales, and support. Content management system 'CMS' ,  manages website content management, promotions,  advertising. Integration of APIs and services with multiple payment gateways to support online transactions. Additionally, Server health and performance are monitored using monitoring tools like Nagios and Zabbix. (Nagios, n.d.; Zabbix, n.d.).


3.3 Internet Connectivity and Network Hardware

With high-bandwidth connections, BookShow guarantees dependable internet access to manage heavy user traffic levels. Furthermore, switches and routers are utilised to provide uninterrupted network communication both inside and outside (Cisco, n.d.). 

3.4 Security Components

BookShow secures its infrastructure using a number of security methods. A software firewall is used to protect the network from unwanted access, whereas a hardware firewall is used to protect the system from external cyber threats. An intrusion prevention system (IPS) and an intrusion detection system (IDS) watch network traffic in order to identify unusual behaviour and stop any assaults. In order to guarantee ongoing service availability, steps are also made to lessen the effects of Distributed Denial of Service (DDoS) assaults.

3.5 Power and Cooling

In the event of a power loss, BookShow employs a UPS as a backup power source to keep the server operational. In order to keep servers and network equipment working at their ideal temperatures, a cooling system is also used. 

4. On-Site Management and Maintenance

4.1 IT Staff and Support Team

The IT department at BookShow is responsible for maintaining and supporting essential services and infrastructure through specialized positions. System administrators monitor network hardware, servers, and storage systems to ensure consistent and smooth operation. Database administrators manage database servers by focusing on improving performance and maintaining data integrity. Network administrators are responsible for both maintaining network connections and implementing security measures to protect the network infrastructure. Moreover, dedicated support workers provide technical help to end users, ensuring efficient use of IT resources throughout the entire company.

4.2 Monitoring

To guarantee the best server and network performance, BookShow employs both human monitoring by IT specialists and automatic monitoring technologies like Nagios and Zabbix. Regular system inspections are carried out by IT staff to ensure system operation and to quickly resolve any issues that may develop. Furthermore, real-time alerts and dashboards are features of monitoring systems that enable proactive administration of server and network activities. BookShow may increase system performance and availability by combining two strategies to cut down on downtime and boost overall operational effectiveness.


4.3 Maintenance

BookShow prioritizes regular updates and patching of software and firmware to maintain security and optimize performance. Additionally, they conduct routine hardware maintenance, including checks and replacements for aging components, ensuring that their infrastructure remains reliable and efficient. These practices contribute to the overall stability and security of BookShow's IT environment.

5. Current IT Challenges
Using the IT infrastructure as a guide, let's sum up the company's challenges:

5.1 High Capital Expenditures (CapEx)


BookShow faces significant capital expenditures primarily due to several factors. These include the continuous costs of purchasing and maintaining the physical servers and network equipment. Also, there are significant initial expenses related to acquiring hardware and software licenses. Moreover, the regular replacement and upgrading of these assets add to the company's overall capital expenditure. Investing in these is crucial to maintain and improve BookShow's IT infrastructure.

5.2 Operational Expenses (OpEx) 

BookShow incurs operational expenses related to various aspects of its IT infrastructure. This includes costs associated with power, cooling systems, and physical space required to house servers and networking equipment. Additionally, operational expenses cover the ongoing maintenance and management of hardware components. Furthermore, BookShow allocates resources for IT staff responsible for the day-to-day management and maintenance of servers, ensuring smooth operation and reliability of its IT environment. These operational expenditures are crucial for supporting the continuous functionality and efficiency of BookShow's technology infrastructure.

5.3 Scalability Problems 

BookShow encounters scalability challenges manifested in two primary issues. Firstly, the company struggles to swiftly add resources to manage surges in demand for significant events or releases. This limitation hinders their ability to efficiently accommodate peak traffic periods. Secondly, in anticipation of peak loads, BookShow tends to over-provision resources, resulting in unnecessary resource allocation and wastage during off-peak periods. These scalability issues highlight the need for a more flexible and efficient resource management approach to better meet fluctuating demand while optimizing resource utilization.

5.4 Frequent Downtime

The current on-premises servers often fail, particularly during peak hours or when there's a surge in demand for popular events. The company is frequently experiencing downtime because its servers cannot handle high traffic volumes. This persistent issue negatively impacts customer satisfaction, causing users to encounter payment interruptions and poor loading times when accessing the website. Consequently, the platform's reliability and overall user experience suffer, potentially leading to customer loss and a decline in trust and reputation.

5.5 Security Threats

Businesses encounter a major difficulty in keeping security patches and updates up to date because of the expensive allocation of resources. Consequently, the system becomes open to unauthorized access and various cyber threats, leading to potential data breaches and security risks.

5.6 Disaster recovery and redundancy

Setting up and maintaining backup and recovery solutions pose challenges for BookShow in terms of complexity and cost. Ensuring data redundancy and availability is crucial but requires significant effort and investment to achieve effectively. These tasks are essential for safeguarding data integrity and ensuring uninterrupted service delivery for BookShow's operations.


5.7 Performance and Monitoring

Server outages or poor performance may go unnoticed for extended periods of time if the monitoring system fails to provide proactive notifications or real-time insights. This could lead to customer annoyance and lost revenue due to the inability to purchase tickets. A non-scalable monitoring system may be overwhelmed by a sudden increase in traffic during well-attended events, resulting in platform slowness or crashes, unpleasant user experiences, and lost revenue as potential buyers abandon their purchases.

6. Impact on Business and Revenue Loss


