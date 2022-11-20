# PHP Ex 9 - Database Queries

> Complete ALL the exercises in this section.  If you need a solution just ask.

		
1.	Write and execute the PHP program ``dbQuery.php`` that demonstrates how to retrieve data from an ``artist`` table in a database called [music](../files/music.sql).

	![alt text](../images/dbQuery_php.png "DB Query")
	
1.	Create a new PHP program called ``albumNames.php`` that prints the names of the albums in ``albums`` table from the ``music`` database.  Use the code from ``dbQuery.php`` for your solution.

1.	Which PHP function connects to the database server?

	- ``mysqli_select_db()``
	- ``mysql_connect_db()``
	- ``mysqli_connect()``
	
1.	Which PHP function selects a database from the server?

	- ``mysqli_select()``
	- ``mysql_select_db()``
	- ``mysqli_select_db()``
	
1.	Using the *phpMyAdmin* tool create a new database, table and some records:

	(a)	Create a database called ``footballDB``

	(b)	Create a table called ``clubs`` with two fields - ``name`` and ``ground``.  Use the data type ``varchar`` and appropriate sizes.

	(c)	Insert at least 5 records into the new table
	
1.	Write a PHP program ``listClubs.php`` that prints the club names in an ordered list (``<ol>``)

1.	Write a PHP script called ``clubTable.php`` that displays ALL the ``clubs`` table data inside a HTML table.

1.	Write a PHP script called ``clubDropdown.php`` that displays the club names inside a dropdown box.
	When a team is selected from the dropdown box, allow the user to click a submit button to submit 
	the selection made to another PHP program called ``clubSelection.php`` that prints a message like 
	*Club selected was Barcelona*
	
1.	Modify the previous program ``clubDropdown.php`` so it becomes a self-submitting PHP script. 
	Clicking the submit button still prints a message and the dropdown box is still available on 
	the same page.

1.	Modify ``clubDropdown.php`` again so the selection made from the dropdown box is *remembered* and selected after the submit button is clicked.  Ask for an explanation of this if necessary.

## Additional Exercise - Music Website Version 1

1.	Using the ``music`` database create the web pages for the video demo shown [here](https://media.heanet.ie/page/553bb67b5bcf48849f31b68e870ced98)
