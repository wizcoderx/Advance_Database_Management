# What is OLAP and OLTP?
<hr>

## OLAP stands for Online Analytical Process and OLTP stands for Online Transaction process

<hr>


<p>In Data Science of Advance database management Systems (ADBMS) OLAP and OLTP are two types of data processing systmes </p>
<p>When i comes to using data to make smarter decisions its not a question of choosing between OLAP and OLTP
Its a question of how to make the best use of both processing, for you situatuon</p>
<br>
<b>Now lets talk about OLAP (Online Analytical Processing):</b><br>

<ul>
<li>The OLAP uses data to gain valuable information.</li>
<li>Its a system for performing multi-dimensional analysis at high speeds on large volumnes of data, the large volumnes of data could be the data warehouse, data mart, or other centralized data store</li>
<li>The core of most of OLAP databases is OLAP cube.</li>
<li>OLAP cubes are multidimensional. They allow users to view data from different perspectives at once. Also users can quickly query, report on and analyze this multi-dimensional data</li>
<li>Here dimensions means simply an element of a particular data set, Example: Sales figure might have several dimensions related to region, time of year, and product models.</li>
<li>The OLAP cube extends the row by column format of a traditional relational database schema and adds layers for other data dimensions</li>
<li>Example: While the top layer of the cube might organize sales by region, data analyst can also drill down into layers for sales by State or City or Specicifc store.</li>
<br>
<b>Uses</b>

<li>OLAP is ideal for tasks such as datamining, business intelligence, and complex analytical calculations</li>
<li>Also well suited for business reporting functions like financial analysis, bugeting, sales forcasting, etc</li>


</ul>


<b>Now lets talk about OLTP (Online Transaction Process):</b><br>

<ul>
<li>The OLTP used to for real-time executions of large number of database transactions by large number of people</li>
<li>OLTP uses non relational databases</li>
<li>It can can process large number of relatively simple transactions, for doing things like insertion, update, delete of data, to do this with rapid processing with response time measured on milliseconds</li>
<li>They also enable milti-user access to the server data while ensuring data integrity and provide indexed data sets for Rapid searching </li>
<br>
<b>Uses</b>
<li>OLTP systems are behind everyday transaction from ATM's, Hotel Reservation, in-store purchase</li>
<li>OLTP can also be used for non-financial transactions, like changing of password and text messages also come under OLTP</li>
<br>

<p> So basically, OLTP does all the infrastructure work and OLAP does the all the analytical work</p>

<hr>

## Differenc between OLAP and OLTP

| Feature                                   | OLAP                                        | OLTP                                                |
|-------------------------------------------|---------------------------------------------|------------------------------------------------------|
| **Optimization Focus**                    | Complex data analysis                      | Processing a massive number of transactions          |
| **User Type**                             | Data scientists, knowledge workers, etc.    | Front-line workers (cashiers, bank tellers, hotel desk, etc.) for customer service applications|


<b>FACT:</b>
<p>OLAP systems may be used to analyze data that leads to business process improvements in OLTP systems, and most organizations do that.</p>

</ul>


