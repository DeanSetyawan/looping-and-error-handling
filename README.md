# looping-and-error-handling
---------------------------
1. looping

- while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. so, as long as boolean condition is True looping will happen till boolean balue is False. usually to prevent its looping endless, we use formula to change value input condition. at the end of looping, we can also make a statement looping end using else that combine with while
- for loop is a control flow statement for specifying iteration, which allows code to be executed repeatedly. A for loop has two parts: a header specifying the iteration, and a body which is executed once per iteration. so, different with while loop for loop already spesific its beginning and end so it can end witout external function to help. for loop also can be nested like if command. for loop nested usually use to make a 2 dimension like table with row and coloum
2 error handling

to handle error, we need to know what kind error can occur in python

- error type

need to note that some reference divided error into 3 part and some into 2 part with different interpretation exception. if divided into 2 part means logical error and exception is same and if divided into 3 part means logical and exception error different. here, we take if error divided into 3 part with each of its definition is

  - syntax error are mistakes in using the language. Examples of syntax errors are missing a comma or a quotation mark, or misspelling a word
  - exception error may occur in syntactically correct code blocks at run time. When Python cannot execute the requested action, it terminates the code and raises an error message.
  - logical error are the most difficult errors to fix as they don’t crash your code and you don’t get any error message. so, logical error occour when we dont get the result we want but the program still running

- handling error

handling error different for each type of error

  - handling syntax error with fix its mistakes in using language like add comma,quotation mark or word spelling
  - handling exception with using try and except. this command make it possible if error occur the program still make an output not stoping in the middle. if error happening we can make output for spesific error with using spesific error name and if not spesific program will read every error with same treatment
  - handling logical error with look detail of program espessially in formula used so we can make our desired output
