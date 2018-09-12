
DoublyLinkedList class extends SinglyLinkedList class. DLLIterator extends SLLIterator.
The following methods are implemented in the DLLiterator.

- hasPrevious()
 This method returns true if there exists an element before the current element (also the current cursor position),else it returns false. 

- Previous()
 This method returns the element before the current element only if such an elememt exists.

- add(x)
 This method adds an element x between the current element and the element returned by call to next(current element). 
 The cursor position is changed to the position of the newly added element x.

- remove(x)
 This method is defined in the SLLIterator class, however it is overriden in DLLiterator class to include and update the previous pointer reference required 
 in Doubly Linked Lists. It removes the current element x. After removal the cursor position changes to the the element before x.


 
