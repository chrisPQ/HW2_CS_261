# HW2_CS_261


You are given a skeleton C code in the following files:
dynArray.h 
dynArray.c 
bag2set.c
stackapp.c


**Implementation of the Dynamic Array
For both Part I and Part II of HW2, you would also need to complete some functions in dynArray.c Download dynArray.c, listed below. Our comments in the code at the beginning of each of these functions will help you understand their purpose. 

void _dynArrSetCapacity(DynArr *v, int newCap) 
void removeAtDynArr(DynArr *v, int idx) 
void removeDynArr(DynArr *v, TYPE val) **


Part I: Convert a Bag into a Set
Complete the function that transforms a bag into a set in bag2set.c Download bag2set.c. A set is a bag that does not have repeated instances of the same element. Your function void bag2set(struct DynArr *da) should call the appropriate functions from dynArray.c Download dynArray.c. In void bag2set(struct DynArr *da), you should also free the memory space allocated to repeated instances of the input bag, since they are not needed any more after exiting the function. 


Part II: Application of Stacks
Stacks can be used to check whether a string of characters (e.g., a mathematical expression) has balanced parentheses of the following three types ( ),  { }, and [ ]. For example, a balanced expression is "{(x + y), [x + (y + z)]}". For a string to be balanced the latest open parenthesis needs to be closed first. Thus, an unbalanced expression: a) Closes an unopen parenthesis; or b)  Closes a parenthesis of a wrong type before closing the right one; or c) Ends before closing an open parenthesis. For example, unbalanced strings are "[x + (y + z)" or "[x + (y + z])". (In this homework, we will not be concerned with the mathematical meaningfulness of the sting, so  the input string may not respect common rules of a correct math expression and still be balanced, e.g., "(x+++++y)" is balanced).


