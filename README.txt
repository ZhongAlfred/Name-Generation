README last updated: [9/19/2015]
Project last updated: [12/29/2015]

Name Generator - Lua Code & Database

What it does:
    Generates random names
    Generates first names (male and female)
    Generates last names
    Names are generated off a weighted frequency scale. What this means is that common names such as 
    "JAMES" will appear more often than names like "ADALBERTO"

 
How Comprehensive is it?
The database that is used by my program (based off http://names.mongabay.com/, which is based off the 2005 census) contains:
    5001 last names (63% of population)
    1219 male first names (90% of male population)
    4275 female first names (90% of female population)

 
Performance?
From a few tests I have run so far, it takes about 1.5 seconds to generate 1000 full names. 
There are probably ways to increase this performance, and I will update my module if I improve upon it.

 
File Size?
The required files are very small:
nameGenerator.lua - 2 kb
names.db - 346 kb


How do I use it in Corona SDK?
An example is given in the main.lua file


How do I use it outside of Corona SDK?
Feel free to adapt the lua file in any way you wish. The database is a SQLite database, 
so most other programming languages should handle it.
