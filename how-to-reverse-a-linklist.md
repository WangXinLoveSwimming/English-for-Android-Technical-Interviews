At the beginning, we declare a variable called cur which point to the head parameter, and declare a variable newHead point to null. 
then we use a while loop, because we're gonna use cur variable to iterator over this list, the loop termination condition is current is not null.
In each loop body, what we have to do is to let the relationship of the two nodes be reversed.
the operation is performed in the following steps:
1. declare a new temporary variable called temp which point to the position of newHead, record the value of newHead.
2. let newHead point to the postion of current variable.
3. let cur variable point to the cur->next value.
4. let newHead's next member varialbe point to the temp's value.

then repeat the same steps in each's while loop body until cur's value is null, we terminate the loop.
at the end, return newHead as return value.
