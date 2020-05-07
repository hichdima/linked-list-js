# linked-list-js
### Linked List data structure implemented in javascript.

Methods included:

1. isEmpty();
Returns true if list is empty

1. insertAtHead(data);
Creates new node and inserts at head

1. insertAtTail(data);
Creates new node and inserts at tail

1. search(value);
Searches for a node with given value.

1. deleteAtHead();
Deletes first node.

1. deleteAtTail();
Deletes last node.

1. deleteAtData(value);
Deletes a node with specific value

1. length();
Returns length of the list.

1. printSelf();
Prints every node.

1. createReversed();
Creates a new reversed linked list.

1. reverseSelf();
Reverses current list.

1. detectLoop();
Returns true if there is a loop in the linked list.

1. findMid();
Returns mid node of the linked list.
If length of the list is even returns lnegth / 2 node.
If length is odd returns (length / 2) + 1 node.

1. removeDublicates();
Removes any node that is a dublicate of already exisiting one.

### Example of how to create a linked list:

```javascript
let myList = new LinkedList();

myList.insertAtTail("1");
myList.insertAtTail("2");
myList.insertAtTail("3");

myList.printSelf();
```
