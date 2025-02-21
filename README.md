# Business-Intelligence-

Preliminaries. You will use a set of open-source, cross-platform tools to implement a data mart and
use it to address a range of business questions:
• Java Development Kit (JDK)
• Java Runtime Environment (JRE)
• Pentaho Data Integration (PDI)
• Pentaho Schema Workbench (PSW)
• MySQL
• MySQL Connector/J
The complete software stack is available for Linux, Windows, and macOS. Compared to more fullfledged commercial BI solutions, the individual elements can be set up quickly on any machine with
minimal system requirements. Our exercise focuses on developing an understanding of concepts
rather than learning a particular vendor's graphical tools – the stack serves this purpose well. Please
refer to the "Lab Setup" section of this document for installation instructions.
Introduction. In this assignment, we use a fictional bicycle wholesaler company named "Big Time
Bikes". The Company has for sale bike components, accessories, clothing, and many different brands
of bikes grouped into three categories - mountain bikes, road bikes, and touring bikes.
"Big Time Bikes" serves customers globally, including Australia, Canada, France, Germany, the United
Kingdom, and the United States. One of the business models used in "Big Time Bikes" is internet sales
that serves individual customers.
"Big Time Bikes" uses a transactional database and data warehouse to support their business. These
database systems cover sales, material management, production, finance, and human capital
management business processes. However, we consider only a part of the system related to internet
sales as a case study to develop a self-service BI system.
In a pilot project, you are tasked with developing a data mart that provides detailed access to sales
data, allows the management team to analyse critical business questions, and supports their decisionmaking. In this pilot project, you will:
1. Create a landing/staging area and populate this database with the data from OLTP database.
2. Create an "Internet Sales" data mart that uses star schema.
3. Define and execute an ETL process to extract, transform, and load data from the
landing/staging area into the Data Mart.
4. Create an OLAP cube for multidimensional sales data analysis.
5. Implement a set of queries to inform management about critical business metrics.
