---
title: Arrays
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is an Array?

An array is a numbered-indexed list.

# What are some examples of information that would be Arrays as opposed to some other data type?

An array could be a list of names, or a group of integers separated by commas.

# What is one way, using Ruby, to retrieve the 6th element in an Array? How about the 8th element? What happens if you try to retrieve the value of the _9999th_ element (or some element that doesn't exist in the array)?

One way to retrieve an element would be to place the position in square brackets [6]. Retrieve the 8th element would look like [8]. If you tried to retrieve a value that didn't exist nil would be returned.

# The previous question asks about finding, for example, the 6th element in an Array. Is it possible to find the **-6th** (Notice the negative symbol!) element in an Array? What does that even mean?

In this case, using a negative integer would ask the program to return the sixth element from the end.

# How would you perform an operation on every element inside an Array?

In this case you would use the each method.

# How do you add elements to an Array?

Elements can be added to an array using << (shovel operator).

# Given the Array `["Laura", "Fiona", "Tori"]`, how would you replace `"Fiona"` with `"Florence"` so that you end up with `["Laura", "Florence", "Tori"]`?

Array[1] = "Florence" would replace '"Fiona"' with '"Florence"'

# What do the methods `push`, `pop`, `shift`, and `unshift` do?

'push' will move and element to the end of an array; 'pop' will remove the last element from array and return it; 'shift' returns the first element of array and removes it from the array; 'unshift' adds an element to the front of an array.

# How do you determine how many elements are in an Array?

The method 'length' will return the number of elements in an array.

# How would you reverse the order of elements in an Array?

The 'reverse' method would reverse the elements in an array.

# How would you convert a String `"Sumeet Jain"` into an Array `["Sumeet", "Jain"]`? How about to `["S", "u", "m", "e", "e", "t", " ", "J", "a", "i", "n"]`? How would you convert the Array back into a String?

Using the'split' method would turn '"Summet Jain"' into `["Sumeet", "Jain"]`. 

Using 'split("") would turn the string into `["S", "u", "m", "e", "e", "t", " ", "J", "a", "i", "n"]`. The 'join' method would then convert this back into an array.