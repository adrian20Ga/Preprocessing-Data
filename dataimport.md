<h1>Data Importation</h1>
<h6>Data Preprocessing-Adrian G-3B</h6>

***
<h3>-Data Table-</h3>
The data tables are ways to present the information to any person with the objective that the person who is reading will be able to understand the data in it. It is composed by rows and colums. Also allow us to create data tables with features such as paging, instant search, export, and multi-column sorting




<img src="https://www.tutorialspoint.com/python_pandas/images/structure_table.jpg" height="300" width="400">


```
import pandas as pd
d = {'one' : pd.Series([1, 2, 3], index=['a', 'b', 'c']), 
   'two' : pd.Series([1, 2, 3, 4], index=['a', 'b', 'c', 'd']), 
   'three' : pd.Series([10,20,30], index=['a','b','c'])}
```




***
***
## <h2>-Data types-</h2>

### Categorical

categorical data is data that is divided into groups or categories. These categories are based on qualitative characteristics such as gender and colors or something else that doesn’t have a number associated with it.

+ Categorical data is divided into groups or categories
+ There is no order to categorical values and variables.
+ Categorical data is displayed graphically by bar charts and pie charts.


<img src="http://intellspot.com/wp-content/uploads/2017/09/example-of-categorical-data-table.png" height="300" width="400">



### Numeric

These data have meaning as a measurement, such as a person’s height, weight, IQ, or blood pressure;


<img src="https://2.bp.blogspot.com/-IUepWeQ3HDA/VO2LddsPkDI/AAAAAAAACNU/pyoF8xyaYsg/s1600/datatypes.png" height="300" width="400">



### Bolean 
This data is primarily associated with conditionals statements. In many programming languages the 0 represents the result False and the 1 represents the result True.It is the data type that has one of two possible values (usually true and false) which is intended to represent two truth values of logic
```
let and = true && false;
let or = true || false;
let not = !true;
```


### Dates
values that represents a point of the time and day. The TIMESTAMP data type consists of a date and time, with optional time zone.

```
import datetime

x = datetime.datetime.now()
print(x)
```

### strings

It is used to represent text rather than numbers as int,float,etc do. It is composed by a set of characters that can also contain spaces and numbers.
``` tcc
#include <stdio.h>
int main()
{
    char c[] = "abcd";
char c[50] = "abcd";
char c[] = {'a', 'b', 'c', 'd', '\0'};
char c[5] = {'a', 'b', 'c', 'd', '\0'};
    return 0;
}
```

***

<h2>Common data formats</h2>


## csv:
It is a simple format for representing a rectangular array (matrix) of numeric and textual values. It is a delimited data format that has fields/columns separated by the comma character.
```
import csv
with open('people.csv', 'r') as file:
    reader = csv.reader(file)
    for row in reader:
        print(row)
```

##json: 
It is a text format easier to the interchange of data. It's origin is from the JavaScript language. It is primarily used for transmitting data between a web application and a server.
```
import json

person = '{"name": "Bob", "languages": ["English", "Fench"]}'
person_dict = json.loads(person)
```


##Xml:
Extensible Markup Language (XML) is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable. 
```
<?xml version="1.0" encoding="UTF-8"?>
<note>
  <to>Tove</to>
  <from>Jani</from>
  <heading>Reminder</heading>
  <body>Don't forget me this weekend!</body>
</note>
```

##xls:
To maintain formatting data we will want to save in a proprietary format like XLS (Microsoft Office Excel), ODS (Open Office spreadsheets) or numbers (Apple Mac), depending on the software we use.
```
from pandas import DataFrame, read_csv
import matplotlib.pyplot as plt
import pandas as pd 

file = r'data/Presidents.xls'
df = pd.read_excel(file)
print(df['Occupation'])
```

***

## <h2>-local vs remote repositories-</h2>

Remote: It is located on one server like GitHub, you can access to the repository in any place.
Local: It is the one which you will make local changes, typically this local repository is on your computer.


***

## <h2>-URL vs API-</h2>

URL:
Universal Resource Locator. It is the specific address that is assigned to each one of the resources available on the network so that they can be located or identified. Thus, there is a URL for each of the resources (pages, sites, documents, files, folders) in internet.

API:
Application Programming Interfaces. It is a set of definitions and protocols that is used to develop and integrate application software, allowing communication between two software applications through a set of rules.

***
## <h2>-Secure data transfer protocols-</h2>


Secure File Transfer Protocol (SFTP).
SFTP transfers files with the Secure Shell (SSH) connection – SFTP is an encrypted network protocol that can enable a remote login to operate over a network that lacks security.

HTTP(Hypertext Transfer Protocol): It allow us to make a request of data an sources, as HTML documents. It is the base of any interchange of data in the web, client-server.

Hypertext Transfer Protocol – Secure (HTTPS).
HTTPS secures websites when users are providing sensitive information like credit card numbers or other personal information.

FTPS: Is an extension to the commonly FTP that adds support for the TLS. Includes the use of server-side public key authentication certificates and client-side authorization certificates.

WebDAV (Web Distributed Authoring and Versioning):Allos the clients to perform remote web content authoring operations. Provides a framewrok for users to create, change and move documents on a server.

***
## <h2>-Describe the procedures for data importing.-</h2>

## CSV
```
data = file.read()
print(data)
file.close()
```
## TXT
```
data = file.read()
print(data)
file.close()
```







.
