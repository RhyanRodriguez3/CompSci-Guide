# Data Structures Guide
PURPOSE
SUMMARY

## What are Data Structures
- A data structure is a way to store, organize, and manage data in a way that allows the programmer to easily access or modify the values within them. An algorithm is the process of searching and modifying the data structure. There are multiple data structures and each have their own use case.
- BigO Notation are measurements used to assess how efficient a data structure is at accessing, inserting, searching, and modifying elements. The lower the BigO notation the better.  
- BigO notations is measured by time complexity equations, which works by inserting the size of the dataset as an integer, and returns the number of operations processed by the computer before the function can finish. Also consider the worst case scenario when judging data structures. Equations below.
   - O(1) 
   - O(log n) gets more efficient as the sice of the data set increases. Ex: Binary Search
   - O(n) the graph of volume of data versus instructions needed for this function is linear meaning that for every element you add to the data set the amount of instructions needed to complete that function will increase by the same amount. Operations required 50 and size of data set 50.
   - O(n log n) Not efficient. as the size of the data set increases instead the slope actually increases as the volume of data does. Graph is an increasing slope.
   - 0(n2) and (211) Inefficient, and exponential slope. 



## Basic Data structures
1. Arrays and ArrayLists
   - An array is a list of similar values that can store anything, but stores values of the same type. Parallel arrays are two or more arrays which contain the same number of elements that have corresponding values in the same position. Two dimensional arrays are arrays within an array where the data is related (think rows and columns).  
   - Elements are the individual items stored in the array.
   - An array has 3 attributes, a name, a type, and a size. In an array, it has to store all type of the same type of information. It's size refers to the total mount of elemtns tat are able to be stored within the array and cannot be changed.
   - There are two different ways to create an array in most languages, you can populate the array with elements or you can set a specific size for the array to populate it later.
   - To get/retrieve/reference infomration that is stored in an array, we use a numerical index. An integer which corresponds to an element within the array.
   - Accessing is 0(1) because it is stored in memory and allows instand access. Serching is O(n) because it is a linear search. Inserting and Deleting is O(n) because you must shift every element to the right to make space for the new element.
   - Pros: Good for storing similar continuous data, gret accessing power, and it is easy to learn and master
   - Cons: Size of the array cannot be changed once initialized, inserting and deleting are not efficient, and can be wasting storage space.
  

 
## Intermediate Data structures
- Stacks
- Queue
- Linked Lists
- Dictionary



## Advanced Data structures
1. ArrayLists is a resizable array. It works because it is a pre-built class, that contains pre-built functions. Functions contain methods.
   - The six commonly used methods are add, remove, get, set, clear, and toArray uses. Autoboxing means the computer assigns an object to the primitive data type.
   - Accessing is O(1). Seraching, inserting, and deleting is O(n) because you have to shift each element.
   - Arrays vs. Arrya lists. Arrays have a fixed size while an array list has a dynamic size. Arryas can store all data types, arraylists can only store objects, you need to create methods with arrays while arraylists is a class with pre-built methods. An arraylist is a class, which menans it requires more memory space and upkeep. Use arrays for smaller tasks where you might not be interacting or changing the data that often an array lists for more interactive programs where you'll be modifying the data quite a bit.
- Tree-based
- Tries
- Heaps
- Graphs



<details>
 <summary>SOURCES</summary>

---
- https://www.youtube.com/watch?v=3b7NiTO8U4g&list=PLzZR2BJ8ICYvXOdi7ML8TYXiSCLO0gMxV

---

</details>
