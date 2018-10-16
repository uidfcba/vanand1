# An Introduction to Databases for Accountants
The purpose of this case is to introduce accounting students to databases. Practicing accountants interact with data from databases whether they realize it or not. For example, transaction-level data captured in accounting systems is stored in databases. Auditors and preparers of financial statements should therefore understand how accounting data is structured and stored in databases. 

In this case, you will assume the role of a preparer of financial statements. You will create a database to store transaction-level data for a fictitious company and then compute some common accounting metrics like revenue and cost of goods sold. Within the database, you will create separate tables to store customer information and customers’ orders. You will also create a table to store information about the company’s products. Finally, you will retrieve data from these tables, merge that data, and transform it into useful numbers like revenue or cost of goods sold.

## Learning Objectives
 * Learn how transaction-level accounting data should be stored.
 * Gain experience with the design of relational databases.
 * Write basic SQL queries to create tables, retrieve data from one table, merge data from multiple tables, aggregate and filter data from one or more tables.
 * Integrate database skills with Python skills by using the SQLite and Pandas packages.
 * Take the perspective of a preparer of financial statements. Retrieve, aggregate, and report financial statement line items that are created from transaction-level data.

## Author Information
Vic Anand, Ph.D.  
Assistant Professor of Accountancy – University of Illinois at Urbana-Champaign  
R.C. Evans Data Analytics Fellow - University of Illinois-Deloitte Foundation Center for Business Analytics<sup>[*]</sup>

## Description of Files in the Repository
 - *Databases_Case.md*: The case document in Markdown format.
 - *Databases_Case.docx*: The case document in Microsoft Word format.
 - Data files (in the Data_files folder):
    - *Customers.csv*: Data on the company's customers.
    - *Orders.csv*: Data on orders from the company's customers.
    - *Order Details.csv*: The line items in each order in *Orders.csv*.
    - *Products.csv*: The products sold by the company.

### Notes
<sup>[*]</sup> I thank The Deloitte Foundation for their generous financial support in preparation of this case.