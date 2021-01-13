# Class 13

## LOCAL STORAGE FOR WEB APPLICATIONS



###  Modernizr to detect support for HTML5 Storage.
    if (Modernizr.localstorage) {
     // window.localStorage is available!
    } else {
     // no native support for HTML5 storage :(
     // maybe try dojox.storage or a third-party solution
}
### USING HTML5 STORAGE

***setItem()***

 named key that already exists will silently  overwrite the previous value.

***getItem()***

with a non-existent key will  return null rather than throw an exception.

*could be rewritten*



    var foo = localStorage["bar"];
    // ...
    localStorage["bar"] = foo;
    
  **methods for removing the value for a given named key**


    interface Storage {
     deleter void removeItem(in DOMString key);
    void clear();
     };

**property to get the total number of values in the storage area**

    interface Storage {
     readonly attribute unsigned long length;
    getter DOMString key(in unsigned long index);
     };


![img](https://javabeat.net/wp-content/uploads/2013/10/html5-localStorage.png)
       

     
### STORAGEEVENT OBJECT PROPERTIES:


1. key
2. oldValue
3. newValue
4. url*

*PROPERTIES*


- key / string/ the named key that was added, removed, or modified


- oldValu / any	/ the previous value (now overwritten), or null if a new item was added

- url*	/ string /	the page which called a method that triggered this change

- newValue/any/the new value, or null if an item was removed


