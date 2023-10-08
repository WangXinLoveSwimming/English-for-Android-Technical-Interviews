The solution is using slow and fast pointers to resolve this task. the time complexity is O(N).
explain the code.
at the beginning, we declare 2 variable called slow and fast. init slow's value to the head the the list, and init the fast to the second node of the list.
then we use a while loop to iterate over this list.
in each loop body, what we do is the check the slow's value whether equals to fast's value.
the operation is performed in the following steps.
1. if slow variable's value equals to fast variable's value, then we return true.
2. if not, assign slow's value to slow's next. and assign fast's value to fast's next, then next;

repeat the same steps in each's while loop body until slow or fast is null, we terminate the loop, then return false.
