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

  # Pointer in array
  Storing a values in subscripted variable much more easy that declaring a many number of variables;
          -> Subscripted variable
                  subscripted variable is a collective name given to the group of similar data.
                  It is also called as "Array".
          -> Passing entire pointer array to the function
                  function_name=(&array_name[0],sizeof_array);//function call should be like this
          -> Array
                  array is static memory allocation type, sometimes shortage or wastage of memory will happpen .
                  To avoid this we need to move "Dynamic memory allocation".
                  -> Dynamic memory allocation,
                          need typecasting because it always return void memory from heap.
                          malloc();
                                  return garbage value.
                          calloc();
                                  return zeros
        
  
  


  

























