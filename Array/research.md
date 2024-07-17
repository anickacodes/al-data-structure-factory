# Array research
Use `CMD + Shift + V` to open this document as a preview in VSCode.
For each of the questions below, use the provided article and your own independent research to write an answer of 3-4 sentences. You don't need to go super deep into details and edge cases unless you have time, you just need the general gist.
[Starting point for research, read here first](https://lucasmagnum.medium.com/sidenotes-array-abstract-data-type-data-structure-b154140c8305)

## Questions(Write out you answers under separate headings)
0. What is an Abstract Data Type?
1. What is an array?
2. What is the difference between a dynamic and a static array?
3. What core operations can a dynamic array do?
4. What is the time complexity for the following operations in a dynamic array data structure?
   1. Searching(looking for something when you don't know an index)
   2. Updating(changing or adding a value) when you know the index
   3. Deleting(removing a value(not like splice)) when you know the index
   4. Deleting like splice
   5. Accessing (retrieving a value) when you know an index
  
### What is an Abstract Data Type?
> An abstract data type classifies how a data structure is used and the behaviors. We can't access time and space complexity here. Provides minimal interaction and behaviors. Must at least retrieve & store data

### What is an array? 
> An array is a data structure that typically stores a collection of elements of the same data type. EAch element can be accessed via index, a position in the array. 

### What is the difference between a dynamic and a static array?
> A dynamic array is capable of changing the original arrays size via adding elements or removing. Can handle various amounts of data efficiently A static array only has a fixed size so can not allocate for new memory. 

### What core operations can a dynamic array do?
> Insert: add an element at the end or at specific index
> Delete: removing an element from the end or at specific index
> Access: getting an element by its index
> Update: change the value of an element at a specific index
> Resize: increase or decrease its memory/capability as elements are added or removed

### What is the Time Complexity for the Following Operations in a Dynamic Array Data Structure?
1. Searching (looking for something when you don't know the index): 
> _O(n)_ becasue you need to potentially _check each element_ in the array until the desired value is found

2. Updating (changing or adding a value) when you know the index:
> _O(1)_ since direct access by index allows for _constant_ time updates

3. Deleting (removing a value when you know the index): 
> _O(n)_ Although finding the element is O(1), _shifting elements after deletion_ takes O(n)

4. Deleting like splice (removing and shifting elements): 
> _O(n)_ Similar to prior deletion since elements need to be _shifted_ to fill the gap

5. Accessing (retrieving a value) when you know the index: 
> _O(1)_ since direct access by index is _constant_ time retrieval