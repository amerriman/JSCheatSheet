* 5 primitives
  Booleans, integers, strings, null, undefined, (symbols)

* functions - expression syntax vs declaration, returns, arguments/parameters,
  -Expression syntax = var name = function() {}
  -Declaration syntax = function name() {}
  -Returns = value returned by function.  Does not automatically print to console
  -parameters = defined in the functions (in the parentheses)
  -arguments = used to call the function (also in the parentheses, but specific when you call the function)

* Loops - for and while
Iterate through instructions
  - FOR  -- has a definite end
  //example
      for (statement 1; statement 2; statement 3) {
    code block to be executed}
  Statement 1 is executed before the loop (the code block) starts.
  Statement 2 defines the condition for running the loop (the code block).
  Statement 3 is executed each time after the loop (the code block) has been executed.
    Example
      for (i = 0; i < 5; i++) {
        text += "The number is " + i + "<br>";}
    From the example above, you can read:
  Statement 1 sets a variable before the loop starts (var i = 0).
  Statement 2 defines the condition for the loop to run (i must be less than 5).
  Statement 3 increases a value (i++) each time the code block in the loop has been executed.
    It will return:
      The number is 0
      The number is 1
      The number is 2
      The number is 3
      The number is 4


  - WHILE -- could go on forever (not good!) unless a condition is met
    while (condition) {
    code block to be executed}
    //example
    while (i < 10) {
    text += "The number is " + i;
    i++;}
      Returns
        The number is 0
        The number is 1
        The number is 2
        The number is 3
        The number is 4
        The number is 5
        The number is 6
        The number is 7
        The number is 8
        The number is 9

* conditionals
  If statements (if, else if, else)
  switch statements

* assignments
  +=
  -+
  *=
  ++
  --

* variables
  -declared
  -hold a value
  -can be changed
  -global or local(aka hidden). Local if defined within a function

* alerts/prompts
  -alert = makes a notice pop up
  -prompt =asks the user to do something/input something.  Always returns a sting, if you need a number you must turn it into an integer.

* scope
  - global variables can be accessed anywhere, even deep into nested statements
  -local varables can only be accessed within the function they were defined in.
  - hoisting - when you redefine a global variable from within a function

* string concatonation
  -adding two strings together.  "2" + "2" = 22
  -"Hi, " + "Ashley" = "Hi, Ashley"

* string, integer, methods
  -string = "this is a string", "2"
  -integer (a number) = 2, 4, 5.4
  -methods = prewritten functions within JavaScript (.toUpperCase())  If it has to have parentheses after it to work, then it's a method?  .length is not a method.

* math operators
  -, +, /, *, %
