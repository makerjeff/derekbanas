#Python Programming in One Video
Based on this tutorial [Python Programming. ](https://www.youtube.com/watch?v=N4mEzFDjqtA&feature=youtu.be&t=2m23s)

##Notes
- 5 main data types in Python: String, Numbers, Lists, Tuples, and Dictionaries.
- 7 arithmetic operators: +, -, *, /, %, ** (exponential), // (discard modulo, rounds down)
- Order of arithmetic operations matter.
- Can do multi-line string using the ''' (triple single quote) method.
- List operators:
    - .append(item)
    - insert(index, item) : inserts 'pickle' into the first slot'
    - remove(<item>)
    - sort()
    - reverse() (reverse sort)
    - del item
- len(item) : get the length of an item.
- max(list) : maximum value of the list.
- min(list) : minimum value of the list.
- Tuples:
    - can't be changed once created.
    - convert to list by using "list(tuple)"
    - convert back to tuple by using "tuple(list)'
- Dictionaries:
    - Uses curly brackets {}
    - (basically like a JS object)
    - key value pairs 
    - accessed with square brackets, or 'dictionary.get('key')'
    - get list of keys dictionary.keys()
    - get list of values dictionary.values()
- logical operators:
    - and, or, not
    - example: if ((age >= 1) and (age <= 18))
- For Loops:
    - for _key_ in _iterable_:
    - range({start value}, {end value})
- While Loops:
    - used when you have no idea how many times you'll need to be looping for.
    - use 'break' to exit entirely out of while loop.
    - use 'continue' to skip the rest of the iteration and move on to the next iteration.
- Functions:
    - same as JS
    - what happens inside a function, stays in a function (unless returned).
    - in order to affect global scope, have to prepend 'global' in front of the global variable.
- Strings:
    - _string.capitalize()_ to capitalize the string.
    - _string.find('word')_ to find position of the word.
    - _string.isalpha()_ to check if it's a letter.
    - _string.isnalnum()_ to check if it's a letter.
    - use len() to get the length of a string.
    - _string.replace('old value', 'new value') to replace something.
    - _string.strip()_ removes white space.
    - _string.split('split character')_ to split a string (same as JS)
    
- File IO (WRITE):
    - test_file = open('filename.ext', 'wb')
    - test_file.mode
    - test_file.name
    - test_file.write(bytes('write data in bytes \n','UTF-8'))
    - test_file.close()
- File IO (READ):
    - test_file = open('test.txt', 'r+')
    - test_file.read()
- File remove:
    - os.remove('test.txt')
    
- Classes (OOP):
    - Classes are the 'objects', functions inside classes are the 'methods' (in relation to JS)
    - variables in a class with two underscores '__var' lets Python know it's a private variable.

    