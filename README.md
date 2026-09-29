Pointers-in-C 
        -Yashavant Kanetkar

# Pointers
  =>To compute address of one variable and value store in a particular address
  =>Two operator are,
  (*) -> value at address/indirectional operator/dereference operator
      To find the value in particular address
  (&) -> address of 
      To find the address of variable

Example:
``int i=3;
``int *j=&i;
``int **k=&j;

  j store address of i
  k store address of j
  *k store address of i

  i give the output 3
  *j give the output 3
  **k give the output 3

NOTE:
  Address of operator always return base address
  Type casting does not affect the pointer
  int *j=&i,
    it means the pointer j store integer variable's address

# Passing arguments in function
  => Passing values in function
  => Passing address in function

sending values in function:
  = call by value method
  Changes in formal arguments(function definition) does not affect in actual arguments(function
  call)
sending address in function:
  =call by reference method
  Changes in formal arguments(function definition) affect in actual arguments(function call)
  Function return more than one value at a time , which is not possible ordinarily.
  
  


  

























