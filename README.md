# An Introduction to Databases for Accountants
One of the important data analytics tasks that an accountant will undertake is merging data from multiple sources. This need might arise when, for example, the accountant wishes to compute profit per customer (i.e. customer profitability analysis) or profit per cost object. Typically, the accountant must retrieve transaction-level data from multiple sources and then merge this data before analyzing it further. Transaction-level data is often stored in databases. Thus, practicing accountants interact with data from databases whether they realize it or not.

The purpose of this case is to introduce accounting students to databases. In this case, you will assume the role of a preparer of financial statements. You will create a database to store transaction-level data for a fictitious company and then compute some common accounting metrics like revenue and cost of goods sold. Within the database, you will create separate tables to store customer information and customers’ orders. You will also create a table to store information about the company’s products. Finally, you will retrieve data from these tables, merge that data, and transform it into useful numbers like revenue or cost of goods sold.

## Learning Objectives
 * Design and create a database for relational data.
    - Write basic SQL to create tables.
    - Learn how data should be stored to reduce or eliminate redundancy.
    - Learn how transaction-level accounting data should be stored.
* Design and create a database from the perspective of a user of financial reporting.
    - Extract information from a database for financial reporting.
        * Retrieve data from one table.
        * Merge data from multiple tables.
        * Aggregate and filter data from one or more tables.
    - Compute financial statement line items from transaction-level data.
* Integrate database skills with Python skills by using the SQLite and Pandas packages.


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