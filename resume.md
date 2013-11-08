---
layout: page
permalink: /resume/
title: Resume
description: "I put things in all the computers"
tags: [resume]
image:
  feature: resume.jpg
---
## Summary of Qualifications

Experienced software engineer bringing to the table a wide range of
knowledge and expertise in software development, and devops. Projects
have ranged from large complex distributed systems to tiny, embedded
real-time platforms. Deeply involved in designing and building release, deployment and
monitoring infrastructure for large commerce sites, as well as
overseeing operations of same.

#### Software development
* Ruby, C, C++, Python, Node.js, ColdFusion, Lua, C#, PHP, Java, Fortran, 
* A number of assembly languages, including Intel 80XXX, PIC, 8051 and variants, along with some exposure to Motorola 68XXXX. Some exposure to Scala, Erlang and a few oddball languanges like CLIPS.
* Rails, Sinatra, Django
* CSS, HTML, Javasript
* Game Engine: Unreal and Torque

#### DevOps
* Years of experience building scalable systems with AWS. Demonstrated
mastery of ec2, s3, etc.
* Extensive work with Postgres 8.3 and 9x as well as some SQL Server and some
MSQL. Proficient generally in SQL, Have deployed and maintained large
postgres clusters in advanced configurations. Production work with Mongo
and Redis. Some hands-on with Cassandra and Riak.
* Elasticsearch -- both deployment and development
* Advanced Puppet
* Automated deployments across environments with LXC, Puppet and git
* Monitoring and instrumentation with Graphite, Nagios. Plenty of hands
on experience with external tools like Webmetrics, Gomez, Monitus and
more.
* Apache, Nginx, HAProxy

## Work Experience

#### 2012 - Present | Turbosquid, Inc. | Senior Engineer
Turbosquid (http://www.turbosquid.com) is the world's largest publisher
of 3d models. My current resposibilities primarily involve around
designing and coding Turbosquid's next-generation content store, as well
as a 3d content production, rendering and publishing toolchain. Much
of this work involves moving building a new production infrastructure on
Linux instances running in AWS. Technology includes:

* Masterless provisioning with Puppet
* LXC Container-based deployment (instead of code-based deployment)
* Service location and distributed configration with zookeeper
* Continuous intergration testing
* git push-based deployments
* Monitoring with graphite, statsd and collectd
* AWS multi-region failover and content replication
* Sharded and replicated NoSQL using postgres 9.3 along with
Elasticsearch as a backend NoSQL store (HStore and plV8)
* Coded primarily in Ruby, Rails, Rails-Api and Node.js
* Traffic routed mailnly through HAProxy and Nginx

#### 2009 - 2012 | iSeatz, Inc. | Senior Engineer, Director of Operations
iSeatz provides turn-key, high-availability multi-lingual travel websites and 
services for major airlines, banks and other partners. Duties at iSeatz
spanned a wide variety of areas, including systems architecture and administration, booking 
webservices architecture and coding, and front-end development. iSeatz is an Agile 
shop, with most coding done in Ruby/Rails, with deployment over clusters of 
Amazon EC2 instances running CentOS Linux. The database in use is a cluster 
of postgres9 servers running over EBS volumes in a raid 1+0 configuration. 

Highlights from iSeatz include:

* Oversaw expanding IT staff as manager and Director. Responsibilities
in addition to day-to-day management included Disaster Recovery
Planning, PCI compliance (external audit), interfacing with clients and
partners, etc.
* Hotel booking web services architecture and coding. Responsible 
for this complex, multi-supplier real-time hotel availability and booking 
engine. Ruby, Rails.
* Back-end systems scaling, optimization and fail-over. Oversaw EC2
production presence grow from a couple of instances, to a large, dynamic stack of load-balancers, front-end 
servers, large application and database server clusters. Wrote
substantial management code in Ruby.
* Payment processing. Designed and coded the multi-currency payment 
back end. The payment system was built to be relatively resilient to
fraud, and fully PCI-compliant. The payment processor also provided the ability 
for our customer service representatives to do full or partial refunds, and 
supports a detailed audit trail for all credit card transactions. (Ruby,
Rails)
* Systems and database administration. Postgres 8 and 9. 

#### 2005 - 2009 | Turbosquid, Inc. | Senior Engineer
Served in a variety of capacities on a number of key projects utilizing an array of technologies. Duties at TurboSquid ranged from design and coding through technical supervision of overseas teams.  Major projects and roles included:

* The GameFlood website. GameFlood is dedicated to delivering third-party game content (“mods”) to gamers in a simple and unobtrusive way. The site also allows online “mashups”, where users can assemble their own unique content. Duties included design and implementation of the Ajax-based Mashup web-interface, the Search and Game invite systems,  and much more. Other aspects of the system were implemented by an offshore team under my technical supervision. Finally, I designed and developed a content-delivery system, described below, used by the site to download and install game content.
* Design and implementation of  the GameFlood content delivery system, an intelligent mod download and installation engine. This system utilizes a ColdFusion-based back end and an intelligent C++ client to allow automatic download and  installation of third-party game content (“mods”). In addition to supporting features like automatic failover and bandwidth optimization, the system is able to install arbitrary content for arbitrary game titles using dynamically downloaded plugins, which encapsulate game and content-specific installation intelligence. The plugins are written in a simple, but complete scripting language, allowing TurboSquid to leverage less expensive development resources to quickly add support for new titles and content. 
* Embedded storefront design and development. Developed and implemented key technologies used to embed TurboSquid and GameFlood storefronts into third-party programs, including both computer games and 3d-modeling software. We have been able to combine C++ frameworks with Gecko rendering engines and Flash/Flex to yield storefronts with the both the functionality of C++ programs and rich interfaces that are simple and inexpensive to develop. In addition to design and coding, these projects required close technical supervision of offshore teams.
* SEO analysis suite. Duties included developing a suite of tools used to optimize TurboSquid page data for Google page rank. Created tools that use sophisticated  NLP techniques to analyze incoming Google referrals and determine optimum page SEO data. Also developed tools to determine keyword rankings vis-a-vis our competitors to provide ongoing business intelligence, as well as feedback used to optimize our SEO strategy.
General TurboSquid website development. Led numerous projects on main TurboSquid website, including the development of an entirely ajax-based storefront and personal asset manager/publisher, as well as a reimplementation of the site search. These typically involved design and coding, as well as extensive supervision of overseas teams.

#### 2001 - 2005 | Lewis Computer Services | Contractor
Responsible for design and implementation of various aspects of a large SQL distributed database application for use by home healthcare providers. Responsibilities include implementation of numerous system data access objects, business objects (objects that overlay business rules on an underlying SQL database), and infrastructure as well as architecture and implementation of a robust loosely synchronized data replication subsystem. This critical subsystem includes such features as automatic conflict resolution, auditability, error recovery and more.

Other responsibilities include automation of certain aspects of code production, documentation and miscellaneous subsystem design. SQL Server 2000, Win32, C++, and Com/Com+ used extensively.

#### 1998 - 2001 | Netpro Computing, Inc | Principal Engineer
Responsible for technical research and new product architecture. Produced code to serve as core technology of NT Active Directory monitoring products. Wrote and designed extensively using COM, WMI and XML to build a distributed and extended infrastructure for AD monitoring products.

Duties also included research into emerging technologies for possible new product direction for company. These areas included wireless network management and security for 802.11B and Bluetooth Scatternets.
Co-architected and coded the ground-breaking Directory Analyzer Active Directory Monitoring service. Some aspects of this large distributed system architecture have been granted a patent (USP# 6,249,883).
Architected and prototyped a network troubleshooting tool using NASA- developed expert system technology (CLIPS) to assist administrators in troubleshooting and diagnosing network failures.

Pursued and prototyped advanced technologies for gathering network and directory performance data from Microsoft Windows 2000 domain controllers, including TDI monitoring, NDIS intermediate driver data capture, Network Packet Provider (NPP) monitoring and real-time Event
Subsystem capture. Much of this research and the resulting code became central to new products.

#### 1994 - 1998 | Netpro Computing, Inc | Senior Engineer
Key architecture and coding for in-house cross-platform distributed service framework, ERIS. Designed and architected networking-enabled in-situ debugging systems, as well as a robust publisher-subscriber messaging system (the ERIS Publisher). This system became a core component of Directory Analyzer (see above).

Key architect and programmer for DS-Expert, a multi-agent Netware NDS monitoring system. Robust monitoring system for Netware Directory Services featuring distributed agents, automatic agent updates, redundant data collection points and more.

Developed in-house programming, testing and documentation standards

#### 1992 - 1994 | BROM Partnership | Partner/Developer
One of two partners in this software development enterprise based in New Orleans, LA and Scottsdale, AZ. Primarily developed and maintained a virus scanning system for VINES/386 servers. Designed and coded both service and client, and ported and debugged the underlying McAfee scan
engine, a difficult and convoluted piece of code at its best, on a monthly basis.

Developed a number of VINES server-based utility services including server-side scripted agents capable of automating repetitive administrative tasks.

Continued to consult, primarily with Compaq Computer Corporation, during this time. Developed, documented and maintained a modem-based wide-area sales information system under OS/2.

#### 1987 - 1992 | COMPAQ Computer Corp | Engineer, Tech Writer
Developed a variety of small manufacturing systems software under DOS, Windows, Unix and HP-3000. Systems coded included an RF-based inventory system, a small DOS multi-tasking system as well as user- friendly front-end interfaces to HP-3000 mini computer-based manufacturing systems. Also developed an email-based wide-area messaging system used in a number of corporate purchasing and requisition applications.

Wrote the user manual for the Vendor Quality System. A complex HP-3000 – based manufacturing system used to track failure rates on out-sourced components. Responsible for a number of other pieces of manufacturing systems documentation

## Selected Patents and Publications
Robot DNA: Building Robot Drive Trains (book with Dennis Clark, ed. Gordon McComb), McGraw-Hill Professional, October 2002.
 
Co-inventor, US Patent No. 6,249,883, System and Method for Monitoring Domain Controllers
