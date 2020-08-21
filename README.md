# python-study-git
### Q1 - Vowel Count
###### Write a function that counts the number of vowels in a given string.
### Solution
###### vowelCount.py
`sum()` **:** <br/>
Syntax: <br/>
`sum(iterable,start)` <br/>
It first sums start,then the elements in the iterable from left to right.

iterable: list, tuple, dict, etc. The elements of the iterables must be numbers. The other data structures can not be used as a parameter of iterables to use sum function. <br/>

start: the value of start is 0 by default. Firstly, start is added to the sum, then iterables are calculated. <br/>

**Example** <br/>
`list = [1,2,3,4]` <br/>
`total = sum(list)` <br/>

If the question was "Count the number of vowels starting from 10 in a given string", then the solution would be <br/>
countVowelStartingWith10.py

### Q2 - Create a Phone Number
###### Write function that takes an array of integers from 0 to 9 -- and returns a string of a form of phone number *(012) 345-6789* with those numbers. 
### Solution
###### createPhoneNumber.py
`format()` **:** <br/>
Syntax: <br/>
`format(value1,value2)` <br/>
This function formats the value paramaters to the placeholder,which is defined by curly brackets { } of a string. <br/> <br/> 
**Example**
>>> '{0}, {1}, {2}'.format('a', 'b', 'c')
'a, b, c'
>>> coord = (3, 5)
>>> 'X: {0[0]};  Y: {0[1]}'.format(coord)
'X: 3;  Y: 5'
>>> 'Coordinates: {latitude}, {longitude}'.format(latitude='37.24N', longitude='-115.81W')


### Q3 - Abbreviate a Two Word Name
###### Write a function to convert a name, which is in the format of *"Harry Potter"*, that has "one space" between the first name and the surname into initials with a dot between them *"H.P"*.



