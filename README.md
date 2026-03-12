
# Array example in Python 2.7
import array

# create an array of integers
arr = array.array('i', [10, 20, 30, 40, 50])

# print original array
print "Original array:"
for i in arr:
    print i

# add a new element
arr.append(60)

print "\nArray after adding an element:"
for i in arr:
    print i
Output Example

Original array:
10
20
30
40
50

Array after adding an element:
10
20
30
40
50
60
