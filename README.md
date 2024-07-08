**Memento** is a behavioral design pattern that lets you save and restore the previous state of an object. It is usually useful for implementing features such as undo or rollback. 
It is done by : 
1. *Originator* --> an object that creates the state of snapshots to the actual owner of that state.
2. *Memento* --> a special object that stores the copy of the object’s state (which is not accessible to any other object except the one that produced it).
3. *Caretakers* --> a restrictive policy(object) that lets you store mementos inside other objects.
