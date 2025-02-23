# test_db
A sample database used to test your applications and database servers

Ported MySQL sample database to Comdb2. Instructive to see Comdb2 indexes and 
foreign keys in action.

Find original MySQL doc at: https://dev.mysql.com/doc/employee/en/index.html

## Where it comes from

The original data was created by Fusheng Wang and Carlo Zaniolo at 
Siemens Corporate Research. The data is in XML format.
http://timecenter.cs.aau.dk/software.htm

Giuseppe Maxia made the relational schema and Patrick Crews exported
the data in relational format.

The database contains about 300,000 employee records with 2.8 million 
salary entries. The export data is 167 MB, which is not huge, but
heavy enough to be non-trivial for testing.

The data was generated, and as such there are inconsistencies and subtle
problems. Rather than removing them, we decided to leave the contents
untouched, and use these issues as data cleaning exercises.


## Installation:

1. Download the repository
2. Change directory to the repository
3. run `./employees <dbname>`

## DISCLAIMER

To the best of my knowledge, this data is fabricated, and
it does not correspond to real people. 
Any similarity to existing people is purely coincidental.

## LICENSE
This work is licensed under the 
Creative Commons Attribution-Share Alike 3.0 Unported License. 
To view a copy of this license, visit 
http://creativecommons.org/licenses/by-sa/3.0/ or send a letter to 
Creative Commons, 171 Second Street, Suite 300, San Francisco, 
California, 94105, USA.
