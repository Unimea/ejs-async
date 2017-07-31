# EJS extended

Temporarily asynchronous method support of ejs(based on v2.5.6), since not supported by official now.

## Usage:  ##

Roughly the same as EJS.

 In addition: 

    - options.fn: 
      set the constructor of function to build the template context, default is 'function', 'async' and 'generator' are available. 
      Customized constuctor is also okay.
    - options.fnOperator: 
      set the operator to excute the function. While 'function' is empty, 'async' is 'await' and 'generator' is 'yield'. 
      Remember to set this when only you want to customize the constructor.
