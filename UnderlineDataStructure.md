[https://www.bigocheatsheet.com/]

### std::unordered_map

- *Underline dta structure* - hash table
the key provied to map is hashed into indies of a hash table.
- *Operation complexity*:

    - search: O(1) , worse case O(n)
    - insert: O(1) , worse case O(n)
    - delete: O(1) , worse case O(n)

    - best case: each values in different bucket
    - worse case: all values in the same bucket

### std::unordered_set

- *Underline data structure:* hash table
- *Operation complexity*:
    
    - search: O(1) , worse case O(n)
    - insert: O(1) , worse case O(n)
    - delete: O(1) , worse case O(n)

    - best case: each values in different bucket
    - worse case: all values in the same bucket

### std::map

- *Underline data structure:* binary search tree (red-black tree). 
- *Operation complexity*:
    
    - search: O(log n)
    - insert: O(log n)
    - delete: O(log n)

### std::set

- *Underline data structure:* binary search tree (red-black tree). 
- *Operation complexity*:
    
    - search: O(log n)
    - insert: O(log n)
    - delete: O(log n)

### std::vector

- *Underline data structure:* dynamic array
- *Operation complexity*:
    
    - accessing by index: best case: O(1), worse case: O(1)
    - inserting or removing at the end: best case: O(1), worse case O(n) because resizing may require.
    - interting or removing in the middle or front: best case: O(n) because shifting all element require, worse case: O(n) because shifting all element require.
    - resizing: best case O(n), worse case O(n).
    - Iterating over: best case: O(n), worse case: O(n)

### std::array

- *Underline data structure:* fixed size array
- *Operation complexity*:
    
    - accessing by index: O(1)
    - insert and delete: O(n) require shift elements
    - copy and assignment: O(n)

### std::list

- *Underline data structure:* double linked list
- *Operation complexity*:
    
    - search:O(n) need to travel all the node
    - insert:O(1) 
    - delete: O(1)
    - access: O(n)

### std::foward_list

- *Underline data structure:* single liked list
- *Operation complexity*:
    
    - search:O(n) need to travel all the node
    - insert:O(1) at front, worse case O(n) as need to travel
    - delete: O(1) at front, worse case O(n) as need to travel
    - access: O(n)
    - iteration: O(n)
  
### std::queue

- *Underline data structure:* std::deque or std::list
- *Operation complexity*:

    - push: back insert O(1), 
    - pop: O(1)
    - iteration: O(n)
    - size: O(1)
    - access: O(1)

### std::deque (double end queue)

- *Underline data structure:* dynamic array but no contiguous memory
- *Operation complexity*:
    
    - access: O(1)
    - insert and delete: front and back O(1), arbitrary position: O(n) require shift elements
    - iteration: O(n)

### std::priority_queue : store elements with associcated proiorities

- *Underline data structure:* std::vector
- *Operation complexity*:

### std::stack

- *Underline data structure:* usually use std::deque or std::vector (because push_back ,pop_back has O(1))
- *Operation complexity*:
    
    - push: O(1)
    - pop: O(1)
    - top: O(1)
    - size: O(1)
    - empty: O(1)