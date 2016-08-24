# SingleLinkedList
SingleLinkedList exercise

Create a single linked list API.

Constructor:
    
    SingleLinkedList():   create an empty linked list

Instance Methods:

    add/remove/read first element
    pushFront(val):    add val in the front. Time complexity ~ o(1)    
    popFront():        remove value in the front Time complexity ~ o(1)
    topFront():        read value in the frount  Time complexity ~ o(1)
    
    add/remove last element
    pushBack(val):     add value in the end. Time complexity ~ o(n)
    popBack():         remove value in the end. Time complexity ~ o(n)
    
    insert/remove elements at arbitrary location
    addBfore(nodeVal,val)   add val before the first occurance of nodeVal. Time complexity ~ o(n) if reference unknown, other wise: Time complexity ~ o(1)
    addAfter(nodeVal,val)   add val after the first occurance of nodeVal. Time complexity ~ o(n) if reference unknown, other wise: Time complexity ~ o(1)
    erase(val):             remove the first occurance of val in the list. Time complexity ~ o(n) if reference unknown, other wise: Time complexity ~ o(1)
    
    miscellaneous
    head():      return the head of the list. Time complexity ~ o(1) 
    find(val):   determine whether val is in the list. Time complexity ~ o(n) 
    isEmpty():   determine whether list is empty. Time complexity ~ o(1)

