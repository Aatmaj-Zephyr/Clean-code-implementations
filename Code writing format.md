The code must strictly adhere to the following tangible guidelines.
A) Naming
  1) Variable and method names must be in camelCase.
  2) Variable names "o" , "l" must not be present.
  3) Single letter variables must not be present anywhere apart from for loops.
  4) Avoid long variable names. Do not exceed variable name size by 25. Variables must consist of minimum two words and maximum 5 words. 
  5) “temp” can be used for temporary scope, but there must not be “temp2”.
  6) 'this' keyword must be used. Follow the syntax this.variable=variable.
  7) Avoid variable names with similar beginnings. 
  8) Class names must be in PascalCase.
  9) Don't use the words 'manager, handler, controller' in class names.
 10) Names must be pronounceable.
 11) Variable names must not contain numbers, and never for using same name twice.
B) Variables
  1) No global variables. Else less than 5% of total number of variables.
  2) No protected variables.
  3) Scope identifiers are compulsary for every variable and function. Specify the default value if necessary.
  4) Don’t use default values. Set every variable to 0 if necessary.
D) Comments
  1) Code must not be commented out.
  2) Variables must have no comments.
  3) Mark important design decisions.
  4) Provide references to algorithms used.
  5) @param must be used for every function for ease of access, but function naming and parameter naming must be clear enough without the param comments.
E) Functions
  1) Methods must never return null.
  2) Methods must never have more than 3 parameters.
  3) Call functions by parameter values wherever possible. (Example point(2,3) must be called as point(x=2,y=3)) This depends on language used. If the language does not allow this, then avoid using two parameters with same type, or include the order in the method name unless the order obvious. 
  4) 
