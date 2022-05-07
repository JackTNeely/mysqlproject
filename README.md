<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=Generator content="Microsoft Word 15 (filtered)">

<!--
 /* Font Definitions */
 @font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:8.0pt;
	margin-left:0in;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:8.0pt;
	margin-left:.5in;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:0in;
	margin-left:.5in;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:0in;
	margin-left:.5in;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:8.0pt;
	margin-left:.5in;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
.MsoChpDefault
	{font-family:"Calibri",sans-serif;}
.MsoPapDefault
	{margin-bottom:8.0pt;
	line-height:107%;}
@page WordSection1
	{size:8.5in 11.0in;
	margin:1.0in 1.0in 1.0in 1.0in;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 ol
	{margin-bottom:0in;}
ul
	{margin-bottom:0in;}
-->

</head>

<body lang=EN-US style='word-wrap:break-word'>
	
	
	
	
<div align="center">
<h1>Preview Coming Soon!</h1>
<!--

<div class=WordSection1>

<p class=MsoNormal align=center style='text-align:center'><span
style='font-size:20.0pt;line-height:107%'>Jack T. Neely <br>
<br>
</span></p>

<p class=MsoNormal>                Hello, my name is Jack Neely. I’m a database
designer. Here, I am showcasing my database development skills by walking
through the process of designing Entity Relationship Diagrams (ERDs), as well
as developing a database in MySQL and testing with queries. </p>

<p class=MsoNormal>My first project is for a local business called “Nora’s
Bagel Bin.”<br>
<br>
</p>

First, we import data from the bagel order form, which was provided for this
project.</p>

<p class=MsoNormal style='text-align:center'><img width=624
height=352 id="Picture 1" src="MySQLProject_files/image001.jpg"
alt="A picture containing table&#10;&#10;Description automatically generated"><br>
<br>
</p>

<br clear=all style='page-break-before:always'>

<p class=MsoNormal>Next, we transform this data into First Normal Form (1NF).<br>
For this project, the transformation was provided.</p>

<p class=MsoNormal><img width=235 height=285 id="Picture 2"
src="MySQLProject_files/image002.jpg"
alt="A picture containing table&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>As you can tell, there are no repeating values in this table
and a primary key has been defined.</p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>Following this, we now transform the data to Second Normal
Form (2NF).</p>

<p class=MsoNormal><img width=624 height=214 id="Picture 7"
src="MySQLProject_files/image003.jpg"
alt="A screenshot of a computer&#10;&#10;Description automatically generated with medium confidence"></p>

<p class=MsoNormal>As you can see, all non-prime attributes are separated by their
functional dependencies. <br>
In other words, primary keys related to other attributes have been separated
into their own tables.</p>

<p class=MsoNormal>You may notice the practicality of this standard from a
business owner’s perspective.<br>
It can sometimes be easier to examine data that has undergone categorization.</p>

<p class=MsoNormal>Note the cardinality representations (1:1 for one-to-one,
and M:1 for many-to-one).</p>

<p class=MsoNormal>Each Bagel Order is unique, and the primary key Bagel Order
ID is used as a Foreign Key in Bagel Order Line Item. Bagels are also unique,
and there can be many bagels in each bagel order line item, as described by
Bagel Quantity.</p>

<p class=MsoNormal>Sequentially, we transform to Third Normal Form (3NF).<br>
This allows us to improve consistency by removing transitive dependencies for
non-prime attributes.<br>
<img width=624 height=293 id="Picture 8" src="MySQLProject_files/image004.jpg"
alt="Diagram&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>Customer details are separated from customer orders to
preserve functional dependence and provide lossless data management. Each Customer
Order contains one Foreign Key, Customer ID, which is referenced by the Primary
Key in Customer Details. We notice here that the cardinality established is
Many to One, as a given customer can place many orders.</p>

<p class=MsoNormal>Finally, we transform the dataset into a working model
schema.<br>
This involved specifying datatypes and formatting value names and attribute names.</p>

<p class=MsoNormal><img width=624 height=223 id="Picture 10"
src="MySQLProject_files/image005.jpg"
alt="A screenshot of a computer&#10;&#10;Description automatically generated with low confidence"></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>That’s it. We have the dataset normalized into 3NF and
transformed into a usable set of tables.<br>
We can perform queries on this, insert into it, create indexes, perform joins,
etc.</p>

<span style='font-size:11.0pt;line-height:107%;font-family:"Calibri",sans-serif'><br
clear=all style='page-break-before:always'>
</span>

<p class=MsoNormal>&nbsp;</p>


<p class=MsoNormal><br>
The second project is to create a database for the business “Jaunty Coffee Co.”<br>
<br>
</p>

<p class=MsoNormal>We can start by creating the database, tables, values, and
attributes:</p>

<p class=MsoNormal><img width=434 height=721 id="Picture 12"
src="MySQLProject_files/image006.png"
alt="Text&#10;&#10;Description automatically generated"></p>

<br clear=all style='page-break-before:always'>

<p class=MsoNormal>For this project, I’m using MySQL Workbench.<br>
<br>
We can execute this selection of the code, and it returns the following:</p>

<p class=MsoNormal><img width=623 height=266 id="Picture 14"
src="MySQLProject_files/image007.png"
alt="Graphical user interface, text, application, Word&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>The execution passes.</p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>Next, we will populate each table with dummy data using
INSERT INTO statements:</p>

<p class=MsoNormal><img width=624 height=70 id="Picture 16"
src="MySQLProject_files/image008.jpg"></p>

<p class=MsoNormal>And execute in MySQL Workbench to view results:<br>
<img width=623 height=257 id="Picture 17" src="MySQLProject_files/image009.png"
alt="Graphical user interface, application&#10;&#10;Description automatically generated with medium confidence"></p>

<span style='font-size:11.0pt;line-height:107%;font-family:"Calibri",sans-serif'><br
clear=all style='page-break-before:always'>
</span>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>Continued:</p>

<p class=MsoNormal><img width=624 height=39 id="Picture 18"
src="MySQLProject_files/image010.png"></p>

<p class=MsoNormal><img width=624 height=258 id="Picture 19"
src="MySQLProject_files/image011.png"
alt="Graphical user interface, text, application, email&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal><img width=624 height=53 id="Picture 20"
src="MySQLProject_files/image012.png"></p>

<p class=MsoNormal><img width=624 height=282 id="Picture 21"
src="MySQLProject_files/image013.png"
alt="Graphical user interface, text, application, email&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal><img width=624 height=38 id="Picture 22"
src="MySQLProject_files/image014.png"></p>

<p class=MsoNormal><img width=625 height=258 id="Picture 23"
src="MySQLProject_files/image015.png"
alt="Graphical user interface, text, application, email&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>Now that we have populated our tables and queried them successfully,
we can create a view.<br>
For this example, let’s create a view EMPLOYEE_VIEW from the EMPLOYEE table. We
will grab every attribute and perform a concatenation on first_name and
last_name to create the attribute employee_full_name and select to view our
results.</p>

<p class=MsoNormal><img width=624 height=69 id="Picture 24"
src="MySQLProject_files/image016.png"></p>

<p class=MsoNormal><img width=624 height=250 id="Picture 25"
src="MySQLProject_files/image017.png"
alt="Graphical user interface, text, application, email&#10;&#10;Description automatically generated"></p>


<p class=MsoNormal>Now let’s create an index on the COFFEE table and test:<br>
<img width=279 height=37 id="Picture 26" src="MySQLProject_files/image018.png"></p>

<p class=MsoNormal><img width=624 height=157 id="Picture 27"
src="MySQLProject_files/image019.png"
alt="Graphical user interface, application&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>We can perform other queries. Here, we will perform a Select
From Where (SFW) query on the COFFEE table with a comparison operand to list
all rows where the price_per_pound of coffee is equal to or less than $5.00.<br>
<img width=277 height=39 id="Picture 28" src="MySQLProject_files/image020.png"></p>

<p class=MsoNormal><img width=623 height=226 id="Picture 29"
src="MySQLProject_files/image021.png"
alt="Graphical user interface, text, application, email&#10;&#10;Description automatically generated"></p>

<br clear=all style='page-break-before:always'>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>Lastly for this project, we can join tables. Let’s join
COFFEE with both COFFEE_SHOP and SUPPLIER. We can do this with two separate
INNER JOIN statements, then ORDER BY coffee_id.<br>
<img width=624 height=50 id="Picture 30" src="MySQLProject_files/image022.png"></p>

<p class=MsoNormal><img width=623 height=248 id="Picture 33"
src="MySQLProject_files/image023.png"
alt="Graphical user interface, text, application, email&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>That’s it for our second project, and that completes our
task. We created an Entity Relationship Diagram (ERD) for “Nora’s Bagel Bin”
and transformed the original data from unnormalized to First Normalized Form
(1NF) to Second Normalized Form (2NF) to Third Normalized Form (3NF) and
finally to useable data properly formatted for database use. After that, we
create a database for Jaunty Coffee Co. using MySQL. We executed our code in
MySQL Workbench to test and output our data. </p>

<p class=MsoListParagraphCxSpFirst style='text-indent:-.25in'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>We
created an entire relational database, </p>

<p class=MsoListParagraphCxSpMiddle style='text-indent:-.25in'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>we
populated several tables using our own data, </p>

<p class=MsoListParagraphCxSpMiddle style='text-indent:-.25in'>3.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>we
created a view that simplified the name attributes for the EMPLOYEE table, </p>

<p class=MsoListParagraphCxSpMiddle style='text-indent:-.25in'>4.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>we
created an index on the COFFEE table,</p>

<p class=MsoListParagraphCxSpMiddle style='text-indent:-.25in'>5.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>we
performed a Select From Where query on the COFFEE table for price_per_pound,
and</p>

<p class=MsoListParagraphCxSpLast style='text-indent:-.25in'>6.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>we
joined the tables COFFEE_SHOP and SUPPLIER on the COFFEE table by related
attributes, ordered by coffee_id, and viewed our final result.</p>

<p class=MsoNormal align=center style='text-align:center'><br>
We accomplished our goals. The PRIMARY KEY (here is that we have inserted into
ourselves an index of database management knowledge.) REFERENCES work_skill(Now
we can inner join select data management organizations that can select from
where we live our expertise.)<br>
<br>
<br>
Thank you.<br>
<br>
<br>
<br>
</p>

<p class=MsoNormal align=center>­ <img width=552 height=864 id="Picture 34"
src="MySQLProject_files/image024.jpg"
alt="Text&#10;&#10;Description automatically generated"></p>

</div>


</div>
-->

</body>

</html>
