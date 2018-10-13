# Python Style Some Sheet

some samples of python-style coding here

###### *now without comments*

'''python
#creating list
four_nones = [None] * 4


a = [3, 4, 5]
b = a
# assign the variable "a" to a new list without changing "b"
a = [i + 3 for i in a]


#filtering list
[item for item in list if 1 <= item <= 5]


#another filtering list
filtered_values = [value for value in sequence if value != x]


#get list of squares
squares = [x**2 for x in range(10)]


#create list len of list with all items = max(first,end)
def max_startEnd_list(list):
    return [max(list[0], list[-1])] * len(list)


#creating list of four lists
four_lists = [[] for __ in range(4)]

#talking name is here
def halve_evens_only(nums):
    return [i/2 for i in nums if not i % 2]


#double every char in string
def double_mult(s):
    return ''.join([x*2 for x in s])

#from list of str to string
letters = ['s', 'p', 'a', 'm']
word = ''.join(letters)


#its beautiful
a, b = b, a
# a = 1, rest = [2, 3]
a, *rest = [1, 2, 3]
# a = 1, middle = [2, 3], c = 4
a, *middle, c = [1, 2, 3, 4]


#loking for
s = set(['s', 'p', 'a', 'm'])
l = ['s', 'p', 'a', 'm']
def lookup_set(s):
    return 's' in s
def lookup_list(l):
    return 's' in l


#working with dictonary
d = {'hello': 'world'}
print d.get('hello', 'default_value') # prints 'world'
print d.get('thingy', 'default_value') # prints 'default_value'
# Or:
if 'hello' in d:
    print d['hello']
    

#print file over line
with open('file.txt') as f:
    for line in f:
        print line
'''



##### Acknowledgments
Thanks to all people of world
