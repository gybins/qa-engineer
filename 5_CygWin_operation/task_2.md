Commands that create the bug1 and events directories:

> $ mkdir bug1
> $ mkdir bug1/events

A command that you use to select queries for a specified period. 

> grep "3./12/2019:21:3.:.." logs/2019/12/apache_2019-12-3*.txt > bug1/main.txt

The commands you use to put logs into the 400.txt and 500.txt files from main.txt:

> grep " 400 " bug1/main.txt > bug1/events/400.txt
> grep "500 " bug1/main.txt > bug1/events/500.txt
