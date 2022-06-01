#### Name: Wei Wang
#### Date: 5/27/2022
#### Course: IT FDN 130 A Sp 22: Foundations Of Databases & SQL Programming
#### GitHubURL: https://github.com/vivian39/DBFoundations-Module07

# Assignment07: Functions

#### Introduction
SQL Functions are a named collection of SQL programming code. They are simply sub-programs, which are commonly used and re-used throughout SQL database applications for processing or manipulating data.

#### Explain when you would use a SQL UDF
In addition to SQL Server's built-in functions, you can create custom functions. These are often called User Defined Functions or just UDFs. There are two basic types of functions; functions that return a table of values and functions that return a single value.
User-Defined Function (UDF) reduces the compilation cost of T-SQL code by caching plans and reusing them for repeated execution. They can reduce network traffic. If you want to filter data based on some complex constraints then that can be expressed as a UDF. Then you can use this UDF in a WHERE clause to filter data.

#### Explain are the differences between Scalar, Inline, and Multi-Statement Functions.
Scalar Functions: A scalar function accepts any number of parameters and returns one value.The term scalar differentiates a single, "flat" value from more complex structured values, such as arrays or result sets.  This pattern is much like that of traditional functions written in common programming language.

Inline Table-Valued Functions: This type of functions returns a result set, much like a view. However unlike a view, functions can accept parameters. The inline function's syntax is quite simple. In the function definition, the return type is set to a table. A return statement is used with a select query in parenthesis.

Multi-Statement Table-Valued Functions: Multi-Statement functions can be used to do some very unique things outside the context of a standard SELECT statement. This type of function returns a table-type result set, but the table is explicitly constructed in script. This can be used to accomplish one of two things: either to process some very unique business logic by assembling a virtual table on the fly, or to duplicate the functionality of an inline function in a more verbose and compiled way. In sort, if you need to select records from an existing a result set, use an inline table-valued function.

#### Summary
SQL functions are very useful when solving SQL database issues. They also improves database efficiency by being used and re-used throughout SQL database applications for processing or manipulating data.
