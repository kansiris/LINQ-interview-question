# LINQ Interview Questions & Answers

> Click :star:if you like the project. Pull Request are highly appreciated. Follow me [@kansiris87](https://twitter.com/kansiris87) for technical updates.

### Table of Contents

| No. | Questions |
|---- | ---------
|1    | [What is Language Integrated Query (LINQ)?](#What-is-Language-Integrated-Query-(LINQ)?)|
|2 | [What are LINQ query expressions?](#What are LINQ query expressions?)|
|3 | [Why LINQ is required?](#Why LINQ is required?)|
|1    | [What are the types of LINQ?](#What are the types of LINQ?)|
|2 | [Explain how LINQ is useful than Stored Procedures?](#Explain how LINQ is useful than Stored Procedures?)|
|3 | [List out the three main components of LINQ? Explain what is the extension of the file, when LINQ to SQL is used?](#List out the three main components of LINQ? Explain what is the extension of the file, when LINQ to SQL is used?)|
|1    | [Define what is Where clause and Let clause?](#Define what is Where clause and Let clause?)|
|2 | [Write the basic steps to execute a LINQ query.](#Write the basic steps to execute a LINQ query?)|
|3 | [Write the basic syntax of a LINQ query in Visual Basic as well as in C#](#Write the basic syntax of a LINQ query in Visual Basic as well as in C#)|
|1    | [In which statement the LINQ query is executed??](#In which statement the LINQ query is executed?)|
|2 | [Explain why SELECT clause comes after FROM clause in LINQ?](#Explain why SELECT clause comes after FROM clause in LINQ?)|
|3 | [Explain what is the use of System.XML.Xlinq.dll?](#Explain what is the use of System.XML.Xlinq.dll?)|
|1    | [Explain what is lambda expressions in LINQ?](#Explain what is lambda expressions in LINQ?)|
|2 | [Explain how LINQ with databases can be used?](#Explain how LINQ with databases can be used?)|
|3 | [Explain what is the difference between Skip() and SkipWhile() extension method?](#Explain what is the difference between Skip() and SkipWhile() extension method?)|
|1    | [In LINQ how will you find the index of the element using where () with Lambda Expressions?](#In LINQ how will you find the index of the element using where () with Lambda Expressions?|
|2 | [Explain how you can assign a lambda expression to a delegate?](#Explain how you can assign a lambda expression to a delegate?)|
|3 | [Explain what is the difference between Statement Lambda and Expression Lambda?](#Explain what is the difference between Statement Lambda and Expression Lambda?)|
|1    | [What is PLINQ?](#What is PLINQ?)|
|2 | [What is the function of the DISTINCT clause in a LINQ query?](#What is the function of the DISTINCT clause in a LINQ query?)|
|3 | [What is the DataContext class and how is it related to LINQ?](#What is the DataContext class and how is it related to LINQ?)|

|1    | [What is the difference between the Take and Skip clauses?](#What is the difference between the Take and Skip clauses?)|
|2 | [What is Object Relational Designer (0/R Designer)?](#What is Object Relational Designer (0/R Designer)?)|
|3 | [Which interface implements the standard query operators in LINQ?](#Which interface implements the standard query operators in LINQ?)|
|1    | [What are standard query operators in LINQ?](#What are standard query operators in LINQ?)|
|2 | [On what parameter does the GroupBy clause group the data?](#On what parameter does the GroupBy clause group the data?)|
|3 | [Explain what are LINQ query expressions?](#Explain what are LINQ query expressions?)|
|1    | [Explain what are compiled queries?](#Explain what are compiled queries?)|
|2 | [Explain how standard query operators useful in LINQ?](#Explain how standard query operators useful in LINQ?)|
|3 | [What is the DataContext class and how is it related to LINQ?](#What is the DataContext class and how is it related to LINQ?)|
|1    | [What is a LinqDataSource control?](#What is a LinqDataSource control?)|
|2 | [Explain how you can differentiate between Conversion Operator 'ToDictionary' and 'IEnumerable' of LINQ?](#Explain how you can differentiate between Conversion Operator 'ToDictionary' and 'IEnumerable' of LINQ?)|
|3 | [What are the different implementations of LINQ?](#What are the different implementations of LINQ?)|

|3 | [Which command-line tool generates code and mapping for the LINQ to SQL component of .NET Framework?](#Which command-line tool generates code and mapping for the LINQ to SQL component of .NET Framework?)|
|1    | [What is the difference between the Select clause and SelectMany() method in LINQ?](#What is the difference between the Select clause and SelectMany() method in LINQ?)|
|2 | [Which extension method do you need to run a parallel query in PLINQ?](#Which extension method do you need to run a parallel query in PLINQ?)|
|3 | [What is the difference between the Select clause and SelectMany() method in LINQ?](#What is the difference between the Select clause and SelectMany() method in LINQ?)|



###  What is Language Integrated Query (LINQ)?

LINQ is a programming model that is the composition of general-purpose standard query operators that allow you to work with data, regardless of the data source in any .NET based programming language. It is the name given to a set of technologies based on the integration of query capabilities into any .NET language

### What are LINQ query expressions?

A LINQ query, also known as a query expression, consists of a combination of query clauses that identify the data sources for the query. It includes instructions for sorting, filtering, grouping, or joining to apply to the source data. The LINQ query expressions syntax is similar to the SQL syntax. It specifies what information should be retrieved from the data source.

###            Why LINQ is required?

LINQ is required as it bridges the gap between the world of data and world of objects.

### What are the types of LINQ?

LINQ to Objects

LINQ to XML

LINQ to Dataset

LINQ to SQL

LINQ to Entities

### Explain how LINQ is useful than Stored Procedures?

Debugging: It is difficult to debug a stored procedure but as LINQ is part of.NET, visual studios debugger can be used to debug the queries

Deployment: For stored procedure, additional script should be provided but with LINQ everything gets compiled into single DLL hence deployment becomes easy Type Safety: LINQ is type safe, so queries errors are type checked at compile time

### List out the three main components of LINQ? Explain what is the extension of the file, when LINQ to SQL is used?

Three main components of LINQ are

Standard Query Operators

Language Extensions

LINQ Providers

The extension of the file used is .dbml

### Define what is Where clause and Let clause?

Where clause: It allows adding some conditional filters to the query.

Let clause: It allows defining a variable and assigning it a value calculated from the data values.

### Write the basic steps to execute a LINQ query.

The following are the three basic steps to execute a LINQ query:

Obtain the data source (The data source can be either an SQL database or an XML file)

Create a query

Execute the query

### Write the basic syntax of a LINQ query in Visual Basic as well as in C#.

In Visual Basic, the basic syntax of a LINQ query starts with the From clause and ends with the Select or Group By clause. In addition, you can use the Where, Order By, and Order By Descending clauses to perform additional functions, such as filtering data and generating the data in a specific order.

In C#, the basic syntax of a LINQ query starts with the From clause and ends with the Select or group by clause. In addition, you can use the where, orderby, and Orderby descending clauses to perform additional functions, such as filtering data and generating the data in a specific order.

### In which statement the LINQ query is executed?

A LINQ query is executed in the For Each statement in Visual Basic and in the foreach statement in C#.

### In LINQ, lambda expressions underlie many of the standard query operators. Is it True or False?

It is true.

### Explain why SELECT clause comes after FROM clause in LINQ?

With other programming language and C#, LINQ is used, it requires all the variables to be declared first. 'FROM' clause of LINQ query defines the range or conditions to select records. So, FROM clause must appear before SELECT in LINQ.

### Explain what is the use of System.XML.Xlinq.dll?

System.Data.Dlinq.dll provides the functionality to work with LINQ to SQL

### Explain what is lambda expressions in LINQ?

Lambda expression is referred as a unique function use to form delegates or expression tree types, where right side is the output and left side is the input to the method. For writing LINQ queries particularly, Lambda expression is used.

### Explain how LINQ with databases can be used?

LINQ supports XML, SQL, Dataset and Objects. Through LINQ to objects or LINQ to Datasets one can use LINQ with other databases. The objects and datasets take care of database particular operations, and LINQ only needs to deal with those objects and not the database operations directly.

### Explain what is the difference between Skip() and SkipWhile() extension method?

Skip() : It will take an integer argument and from the given IEnumerable it skips the top n numbers

SkipWhile (): It will continue to skip the elements as far as the input condition is true. It will return all remaining elements if the condition is false

### In LINQ how will you find the index of the element using where () with Lambda Expressions?

In order to find the index of the element using where () with the lambda expression
Where ( ( i, ix ) => i == ix);

### Explain how you can assign a lambda expression to a delegate?

To assign a lambda expression to a delegate
Delegate int del (int i);
Del myDelegate=x=>x*x;
Int j = myDelegate (4); //j=16

### Explain what is the difference between Statement Lambda and Expression Lambda?
 
 Expression Lambdas are extensively used in the construction of Expression Trees.To create expression trees statement lambdas cannot be used
 
 ### What is PLINQ?

PLINQ stands for Parallel Language Integrated Query. It is the parallel implementation of LINQ, in which a query can be executed by using multiple processors. PLINQ ensures the scalability of software on parallel processors in the execution environment. It is used where data grows rapidly, such as in telecom industry or where data is heterogeneous.

PLINQ also supports all the operators of LINQ. In addition, you can query 'collections by using PLINQ. It can also run several LINQ queries simultaneously and makes use of the processors on the system. Apart from this, PLINQ uses parallel execution, which helps in running the queries quickly. Parallel execution provides a major performance improvement to PLINQ over certain types of legacy code, which takes too much time to execute.

### What is the function of the DISTINCT clause in a LINQ query?

The DISTINCT clause returns the result set without the duplicate values.

### What is the DataContext class and how is it related to LINQ?

After you add a LINQ to SQL Classes item to a project and open the O/R Designer, the empty design surface represents an empty DataContext class ready to be configured. The DataContext class is a LINQ to SQL class that acts as a conduit between a SQL Server database and the LINQ to SQL entity classes mapped to that database. This class contains the connection string information and the methods for connecting to a database and manipulating the data in the database. It is configured with connection information provided by the first item that is dragged onto the design surface.

### What is the difference between the Take and Skip clauses?

The Take clause returns a specified number of elements. For example, you can use the Take clause to return two values from an array of numbers. The Skip clause skips the specified number of elements in the query and returns the rest. For example, you can use the Skip clause to skip the first four strings in an array of strings and return the remaining array of string.

### What is Object Relational Designer (0/R Designer)?

The 0/R Designer provides a visual design surface to create LINQ to SQL entity classes and associations (relationships) that are based on objects in a database.

### Which interface implements the standard query operators in LINQ?

The standard query operators implement the IEnumerable<T> or the IQueryable<T> interface in C# and the IEnumerable(Of T) or the IQueryable(Of T) interface in Visual Basic.

### What are standard query operators in LINQ?

The standard query operators in LINQ are the extension methods that form the LINQ pattern. These operators form an API that enables querying of any .NET array or collection. It operates on sequences and allows you to perform operations, such as determining if a value exists in the sequence and performing an aggregated function, such as a summation over a sequence.

### On what parameter does the GroupBy clause group the data?

The GroupBy clause groups the elements that share a common attribute.

### Explain what are LINQ query expressions?

Query expression is nothing but an LINQ query. It is a combination of query clauses that identifies the data sources for a query. It contains information for sorting, filtering, grouping or joining to apply to the source data. It determines what information should be retrieved from the data source.CV.

### Explain what are compiled queries?

In compiled LINQ queries, the plan is cached in a static class and static class is a global cache. Rather than preparing the query plan from scratch, LINQ prepares plan using stating class object.

### Explain how standard query operators useful in LINQ?

Standard Query Operators useful in LINQ are

Get a total count of elements in the collection

Order the results of a collection

Grouping

Computing average

Joining two collections based on matching keys

Filter the results

### Explain what is 'LINQ to Objects'?

When LINQ queries any IEnumerable(Of T) collection or IEnumerable directly without the use of an intermediate LINQ provider or API such as LINQ to SQL or LINQ to XML is referred as 'LINQ to Objects.'

### What is a LinqDataSource control?

The LinqDataSource control enables you to use LINQ. in an ASP.NET Web page by setting the properties in the markup text. You can use the control retrieve or modify data. It is similar to the SqIDataSource and ObjectDataSource controls in the sense that it can be used to declaratively bind other ASP.NET controls on a page to a data source. The difference is that instead of binding directly to a database or to a generic class, the LinqDataSource control is designed to bind a LINQ enabled data model.

### Explain how you can differentiate between Conversion Operator 'ToDictionary' and 'IEnumerable' of LINQ?

To solve the conversion type problems 'IEnumerable' and 'ToDictionary' conversion operator are used.
'ToDictionary' conversion operator is the instance of Dictionary (k, T). The 'keySelector' predicate recognizes the key of each item, while 'elementSelector, is used to extract each single item, if it is given.
Extension method on 'IEnumerable' is.AsEnumerable. AsEnumerable simply returns the source sequence as an object of type IEnumerable <T>.

### What are the different implementations of LINQ?

The different implementations of LINQ are:

LINQ to SQL - Refers to a component of.NET Framework version 3.5 that provides a run-time infrastructure to manage relational data as objects.

LINQ to DataSet - Refers to a component that makes it easier and faster to query over data cached in a DataSet object.

LINQ to XML - Provides an in-memory XML programming interface.

LINQ to Objects - Refers to the use of LINQ queries with any IEnumerable or IEnumerable(T) collection directly, without the use of an intermediate LINQ provider or API, such as LINQ to SQL or LINQ to XML.

### Which command-line tool generates code and mapping for the LINQ to SQL component of .NET Framework?

The SqlMetal.exe command-line tool generates code and map the LINQ to SQL component.
Name the control that exposes the LINQ features to Web developers through the ASP.NET data-source control architecture.
The LinqDataSource control exposes the LINQ features to Web developers through the ASP.NET data-source control architecture.

### What is the difference between the Select clause and SelectMany() method in LINQ?

Both the Select clause and SelectMany() method are used to produce a result value from a source of values. The difference lies in the result set. The Select clause is used to produce one result value for every source value. The result value is a collection that has the same number of elements from the query. In contrast, the SelectMany() method produces a single result that contains a concatenated collection from the query.

### Which extension method do you need to run a parallel query in PLINQ?

The AsParallel extension method is required to run a parallel query in PLINQ.
    
 ### What is the difference between the Select clause and SelectMany() method in LINQ?

In both the Select clause and SelectMany() method a result value will be generated out of the source of values.

The difference between both of them is in the result set. The Select clause will generate one value for every source value.

The result value is a collection which is having the same number of elements from the query.

On the other side, theSelectMany() method generates a single result that has a concatenated from the query.
