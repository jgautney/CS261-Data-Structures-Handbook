# Dictionary

A Dictionary is a data structure that uses a Key:Value system to store data in an unordered way.

# In Memory

In memory, a Dictionary looks like this:

![Image of dictionary in Memory](images/dicitonary.png)

In a dictionary, when a value is added it is entered with a unique key.  When the key is called it is used to locate the value in O(1) time.

# Operations

A dictionary supports the following operations:

* Get Item: Returns the value when given the associated key.  This is an O(1) operation as the key is a pointer directly to the related value.
* Remove Item: Deletes the value when given the associated key.  It is an O(1) operation for the same reason as above.
* Add item: adds item to the dictionary with associated key.  O(1) time for the same reason as above

# Use Cases

A dictionary is useful when you want to have a collection of data that you can retirieve in O(1) time.



# Example

```
my_dict = {1 : "Grill" , 3 : "Hotdog", 100 : "Beer" }
my_dict[5] = "Guest"
print(my_dict)
```