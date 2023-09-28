## Objectives:
The main objective of the project is to create and manage relationship using daatasets entity mapping between multiple datasets and form a master table.
 * Finding the number of records in each datasets.
 * Create the relationship between Transaction Data and Loan Data using account_id as a relationship factor by inner join.
 * Mapping Account Data and Order Data using account_id as a factor by inner join.
 * Joining the Card Data and disposition Data using disp_id as a relationship factor by inner join.
 * Creating the relationship between merged Card and Disposition Data with Client Data using client_id as a factor by inner join.
 * Entity Mapping the Card, Disposition and Client Data with District Data using district_id as a mapping relationship by inner join.
 * Mapping the relationship between Merged Account and Order Data with Card, Disposition, Client and District Data using district_id as a factor by left join.
 * Forming Master Table by joining the merged Account, Order, Card, Disposition, Client, District Data with merged Transaction Data and Loan Data using account_id as a factor.
    The image gives detailed brief about how the relationship mapping works.

   ![image](https://github.com/Balajimohan18/SQL-Projects/assets/136687240/fa45e569-8150-4e3d-b086-4be73efaa9ea)
