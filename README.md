# Singly-Linked-Lists

Implementation singly linked list with some array method 

# push
adding new node to the end of the link list

<--pushing pseudocode-->

This function should accept a value

Create a new node using the value passed to the function

If there is no head property on the list, set the head and tail to be the newly created node

Otherwise set the next property on the tail to be the new node and set the tail property on the list to be the newly created node

Increment the length by one

Return the linked list

<-------------------------->


# pop

Removing a node from the end of the Linked List!

Popping pseudocode

If there are no nodes in the list, return undefined

Loop through the list until you reach the tail

Set the next property of the 2nd to last node to be null

Set the tail to be the 2nd to last node

Decrement the length of the list by 1

Return the value of the node removed


<-------------------------->

# Shift

Removing a new node from the beginning of the Linked List!

Shifting pseudocode

If there are no nodes, return undefined

Store the current head property in a variable

Set the head property to be the current head's next property

Decrement the length by 1

Return the value of the node removed


<-------------------------->

# UnShift

unshift pseudocode

This function should accept a value

Create a new node using the value passed to the function

If there is no head property on the list, set the head and tail to be the newly created node

Otherwise set the newly created node's next property to be the current head property on the list

Set the head property on the list to be that newly created node

Increment the length of the list by 1

Return the linked list

<-------------------------->

# Get

Retrieving a node by it's position in the linked list

get pseudocode

Retrieving a node by it's position in the linked list

This function should accept an index

If the index is less than zero or greater than or equal to the length of the list, return null

Loop through the list until you reach the index and return the node at that specific index

<-------------------------->

# Set

Changing the value of a node based on it's position in the Linked List

set pseudocode

This function should accept a value and an index

Use your get function to find the specific node.

If the node is not found, return false

If the node is found, set the value of that node to be the value 
passed to the function and return true;

<-------------------------->

# Insert

adding a node to the linked list at a specific position

insert pseudocode

If the index is less than zero or greater than the length, return false

If the index is the same as the length, push a new node to the end of the list

If the index is 0, unshift a new node to the start of the list

Otherwise, using the get method, access the node at the index - 1

Set the next property on that node to be the new node

Set the next property on the new node to be the previous next

Increment the length

Return true

<-------------------------->

# Remove

Removing a node from the Linked List at a specific position

Remove pseudocode

If the index is less than zero or greater than the length, return undefined

If the index is the same as the length-1, pop
If the index is 0, shift

Otherwise, using the get method, access the node at the index - 1

Set the next property on that node to be the next of the next node

Decrement the length

Return the value of the node removed







