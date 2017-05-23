[TOC]
***

I wrote down those study notes to help me summarize what I've read and learn from Python for Kids :)
#Part 1
## Strings,Lists,Tuples,and Maps
### Strings
#### Handling problems

```
# use three single quotes (''') to solve the handling problems
silly_string = '''He said, "Aren't can't shouldn't wouldn't."'''
# backslash (\) can help Python to ignore the quotes inside the string
# ' can't use inside the ' ' 
# " can't use inside the " " 
single_quote_str = 'He said, "Aren\'t can\'t shouldn\'t wouldn\'t."'
double_quote_str = "He said, \"Aren't can't shouldn't wouldn't.\""
```
#### Embedding Values in Strings
```
# When using more than one placeholder, be sure to wrap the
#replacement values in parentheses
print('How did the soggy Easter Bunny dry himself?')
joke_text = 'With a %s %s '
word_1 = 'hare'
word_2 = 'dryer.'
print(joke_text % (word_1, word_2))
print(joke_text % ('hair ' * 3, 'dryer'))
```
### Lists
#### Items
```
'''
lists start at index position 0, so the first item in a list is 0, the second is 1, and
the third is 2.
'''
wizard_list = ['spider legs', 'toe of frog', 'eye of newt',
'bat wing', 'slug butter', 'snake dandruff','double whooper']
print(wizard_list[0],wizard_list[4])
#change an item in a list
wizard_list[2] = 'eye of cat'
print(wizard_list)
#show subset of the items
'''
[2:5] meand show the items from index
position 2 up to (but not including) index position 5
in other words, items 2, 3, and 4.
'''
print(wizard_list[0:4])
'''
Lists can be used to store all sorts of items, like numbers
mixtures of numbers and strings and store other lists
'''
num_list = [5,55,2,6]
str_and_num_list = [5,'haha',333,'fuck']
mix_list = [num_list, wizard_list]
print(num_list, str_and_num_list, mix_list)
```
#### Adding and Removing Items

```python
wizard_list = ['spider legs', 'toe of frog', 'eye of newt',
'bat wing', 'slug butter', 'snake dandruff','double whooper']
#append adds an item to the end of a list.(add one element)
wizard_list.append ('bear burp')
print(wizard_list)
# remove items
del wizard_list[0:4]
# remove first to fourth items
print(wizard_list)
```



#### List Arithmetic

```
# adding and multiply
list1 = [1,2,4,5]
list2 = [2,'d','d']
print(list1 + list2)
list3 = list1*3
print(list3)
```

### Tuples

```
'''
A tuple is like a list that uses parentheses,
The main difference between a tuple and a list is that a tuple
cannot change once you’ve created it.
'''
tup = (2,2,2,4)
```

### Maps

```
#a map are enclosed in braces ({}),
#key:value
# it can be deleted and replaced the values
map={'Michael':'12','Tom':'45'}
print(map['Tom'])
map['Tom'] = 444
print(map)
del map['Tom']
print(map)

```



### Puzzles (my answers)

