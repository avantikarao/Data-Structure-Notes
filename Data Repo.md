List Comprehension: Method to concisely create lists
- Commonly used when a new list: 
  - is result of some operations applied to all of its member of another sequence/iterable
  - Or elements that satisfy a certain condition

List comprehension consists of:
  - Square Brackets containing an expression
  - For clause
  - Then a zero or more for or if clauses


tuples: immutable sequence data-type object

- declared with parenthesis
- () empty tuple
- (50,) singleton ( comma needed)
- sliceable therefore indexable 

Iterator Function: A function that returns an object that is iterable.
Example:
- The range() function returns an iterable collection of integer values that fit the criteria of the arguments
- lets you loop through it 


Map()
- built-in that applies to a given function to every item in the givem sequence and returns result
- functional programming 


filter()
- grabs certain values from an iterable also long as it is true
- built-in that filters out items in the sequence if the function is true and returns result

set() 
- are well-deifned collection of distinct obj, considering as an onject in its own right 
- has no order 
- container of values, thereofore should no hold duplicates 

  membership:
    -element of:
    when a specific item is a memeber of set
    x E a 
    
    subset:
    any set whose its members are elements of another set
 
 Operators 
    Union: The union of set A and set B is the result of all its member into a singular set with duplicate members discarded
    a u b
    
   Intersection: The intersection of set A and B is members that are present in both sets
   a n b 
    
   Subtraction: it doesn't really exist… The act of A - B results to removing the members that exist in set B from set A.
    a - b 
    
   Symmetric Difference: Elements that are in either set, BUT they cannot intersect
    
   Universe: A set that is defined to contain every possible members … all the values in our data set.
    
   Complement: A complement of set A will be the set that contain members from the Universe set that doesn’t exist in set A


Sets: A set is an unordered collection with no duplicate elements 
- in computer memeory it creates unique memory adresses for each value in a set


Dictionary: (associative Array)

- data type that stores a collection of (key,value) pairs. such that each is unique in the collection
- we get to have a system of indexes 
- each value in the array has the memory adress with the index value when u delete a value in t list everything shifts over so every adress changes
- we can delete a value from a dictionary, and it will still maintain its dataset size/length as long the key is preserved
- must be immutable data type 
    - strings, num, tuple

- one adress cannot have two values
- dictionary will maintain order of insertion 

{} empty dictionary

-----------------------------------
item = (address, value)

for adress, value in A.items():
-----------------------------------


