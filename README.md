
### Get this product for $5

<i>Packt is having its biggest sale of the year. Get this eBook or any other book, video, or course that you like just for $5 each</i>


<b><p align='center'>[Buy now](https://packt.link/9781786460448)</p></b>


<b><p align='center'>[Buy similar titles for just $5](https://subscription.packtpub.com/search)</p></b>


# Implementing Qlik Sense
This is the code repository for [Implementing Qlik Sense](https://www.packtpub.com/big-data-and-business-intelligence/implementing-qlik-sense?utm_source=github&utm_medium=repository&utm_campaign=9781786460448), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Qlik Sense is a leading enterprise for business intelligence solutions. Qlik Sense helps making informed decisions based on the data organizations have.

This book will teach you how to effectively use Qlik for optimum customer satisfaction. You will observe a metamorphosis from a developer to a consultant who is capable of building most apt BI solutions for your clients. The book will take you through several business cases – this will give you enough insight to understand the need of the client clearly and build a BI solution that meets or exceeds their expectation. Starting from the pre-project activities, you will go to actual execution of the project, implementation, and even maintaining it. This book will give you all the information - right from strategy to requirement gathering to implementing BI solution using Qlik Sense.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
REM Full Load from Excel file "Sales" ;
Sales:
LOAD
      Region,
      SalesID,
      Product,
      SalesAmt,
      LastModifiedDate
FROM [lib://Chapter 6/Sales.xlsx]
(ooxml, embedded labels, table is Sheet2); 

REM Store the data into Qlik Data Mart i.e QVD;
Store Sales into [lib://Chapter 6/Sales.qvd];

Drop table Sales;
```

The examples provided in the chapter will require you to have Qlik Sense Desktop installed
on your PC. The Qlik Sense Desktop is a free software available for download from Qlik
web site. The software runs on 64 bit Windows 7, 8.1, or 10 operating system.
Recommended config is 4GB Ram or more with Intel i3 or higher processor.
The examples provided use Microsoft Access database. The user just needs Microsoft
Access odbc driver to connect to the mdb file from Qlik Sense Desktop.

## Related Products
* [Learning Qlik® Sense: The Official Guide](https://www.packtpub.com/big-data-and-business-intelligence/learning-qlik®-sense-official-guide?utm_source=github&utm_medium=repository&utm_campaign=9781782173359)

* [Qlik Sense® Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/qlik-sense-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781782175148)

* [Learning Qlik Sense®: The Official Guide - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/learning-qlik-sense-official-guide-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785887161)
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781786460448">https://packt.link/free-ebook/9781786460448 </a> </p>