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
### Solution
###### abbreviateName.py
`join()` **:** <br/>
Syntax: <br/>
`join(iterable)` <br/>
It is a string method that joins the elements of iterables, which are list,tuple,dict,set and string, with a string seperator  <br/> <br/> 
**Example**
# .join() with lists
numList = ['1', '2', '3', '4']
separator = ', '
print(separator.join(numList)) <br/>

`split()` **:** <br/>
Syntax: <br/>
`split(seperator,split_MAX)` <br/>
This method returns a string list after breaking the string with a specified seperator.<br/>
seperator : splits the string with a specified delimeter. If it is not specified, splits the string with respect to "white space" character by default.<br/>
split_MAX : decides the maximum number of times given string to be splitted. It's end of the line by default. <br/>
**Example**
txt = "apple#banana#cherry#orange"

# setting the maxsplit parameter to 1, will return a list with 2 elements!
x = txt.split("#", 1)
print(x)

Output
['apple', 'banana#cherry#orange']

### Q4 - Recursive Sum of All The Digits in a Number
###### Write a function calculate the sum of the digits of a given natural number recurisely until the number becomes one digit. 
### Some Examples 
26 --> 2 + 6 = 8
87 --> 7 + 8 = 15 --> 1 + 5 = 6
99999999999271 --> 9 + 9 + 9 + 9 + 9 + 9 + 9 + 9 + 9 + 9 + 9 + 2 + 7 + 1 = 109 --> 1 + 9 = 10 --> 1 + 0 = 1 
### Solution
###### recursiveDigits.py


### Q5 - Travel Unique Places
######  Imagine you're in a travel to visit some countries in the Europe -- you want to travel every country withour serial. If you went the same where "n" times, you're looking the integer list, a unique number corresponds to a country, in your hand to see your route from starting till the nth visit of the same country.
The number "n" terminates the visit after n times travel the same country. Create a list of numbers corresponds to the countries visited.
### Example
Let's say your route is Berlin --> Munich --> Paris --> Oslo --> Vienna --> Munich. <br/>
List is ls = [ 1, 2, 3, 4, 5, 2 ]
### Some Examples 
26 --> 2 + 6 = 8
87 --> 7 + 8 = 15 --> 1 + 5 = 6
99999999999271 --> 9 + 9 + 9 + 9 + 9 + 9 + 9 + 9 + 9 + 9 + 9 + 2 + 7 + 1 = 109 --> 1 + 9 = 10 --> 1 + 0 = 1 
### Solution
###### recursiveDigits.py

