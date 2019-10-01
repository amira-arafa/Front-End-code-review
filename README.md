# Front-End-code-review

#### General checklist:
1)  The number of spaces per indentation-level (2 spaces).
2)  Capitalization of the first letter of a comment.
3)  Make sure you remove commented out code.
4)  Do not write comments for what you are doing, instead write comments on why you     are doing and For every method there should be sufficient comments about its  function,parameters and the exception it might be thrown.
5) No duplication of code.
6) Removed unused packages from NPM.
7) Code does not contain deprecated elements & attributes
8) Code is Readable ,If any one reads the code must be able to understand it without need any explanation.
9) Use single quotes for string except to avoid escaping.
10) No multiple empty lines,avoid empty lines in the end and beginning of functions (before the closing and opening brackets).

#### HTML:
1)  do not Use Inline Styles on your code.
2)  do not Use Inline JavaScript.
3)  Make Use of Semantic Elements.
4)  Use proper attributes for images and links. Like (“Alt“,”Title”)



#### JavaScript&ES6/7:
1)  Curly braces opening at the same line of if statement or for loop and keep the else statement on the same line as their curly braces.
2)  Print semicolons at the end of statements.
3)  No hardcoded values, use constants values (don`t use calculated values inside the variables).
4)  Naming must be descriptive and all names should be consistent across the project, use camelCase naming convention.
5)  Remove unused imports/variables .
6)  Print spaces between brackets in object literals. { key: “value” }.
7)  consistent spacing inside array brackets [ 1, 2 ].
8)  Avoid multiple if/else blocks.(use switch instead).
9)  For ternary operator in multi-line place the ? and  : on their own lines.
10)  Code has no any linter errors or warnings.
11)  No console.logs.
12)  When you use console.log for testing a result use it like this console.log(‘valueName’ , val) a small string before your value can make tracing more easy.
13)  No debugger statements.
14)  A method should not be larger than 40 lines of code. The idea is, the function should be always viewable on a single screen without scrolling.
15)  Place Scripts at the Bottom of Your Page.
16)  Avoid Globals : Global variables are a terribly bad idea.
17)  Your functions should do one thing only on one level of abstraction.
18)  Use Shortcut Notations - like ternary functions.
19)  Try to use pure functions.
20)  No function declarations in nested blocks.
21)  Declare Variables Outside of the For Statement.
22)  Use {} Instead of New Object().
23)  Long List of Variables? Omit the "Let" Keyword and Use Commas Instead.
24)  Code does not contain inline JavaScript event listeners.
25)  Error handling: For any external request , should be handle any error might be accrued ,Error messages should be found in one shared file.
26)  Edge cases handling:Cases like Null , Zero , NaN and negative should be handled.
27)  Always use === instead of ==.
28)  Arrays indexes should be always within bound.
29) APIs calls should be centralized in one file (Service) to avoid logic duplication.
30)  Use const over let (avoid var).
31)  Use arrow functions instead of var that = this.
32)  Use destructuring assignment for arrays and objects.
33)  Use spread/rest operator.
34)  Use default values.
35)  Use template literals.
36)  Use Promises or Asyns/Await. Rejection is handled.



#### Frameworks and libraries:
  ##### React:

1)  Put the > of a multi-line JSX element at the end of the last line instead of being alone on the next line. 
Ex:<Component
    className="test"
    color="test"/>
2)  Functional components for components that don't use state.
3)  No api calls in containers, delegate to Sagas.
4)  No state updates in loop.
5)  No useless constructor.
6)  Avoid using an array index as key prop, instead use a unique ID.

#### Version control system:
   ##### Git:
1) Commits are small and divided into logical parts.
2) Commits messages are small and understandable.
3) Use branches for new features.

#### Style
1) Consistent naming conventions are used (BEM, OOCSS, SMACSS, e.t.c.).
2) Use Hex color codes #000 unless using rgba().
3) Avoid !important.
4) Do not animate width, height, top, left and others. Use transform instead.
5) Use same units for all project.
6) Avoid inline styles.
7) Use lower case letter for selectors and properties.
8) Put spaces after “:” in CSS property declarations
(Example: color:#FF0000 – Bad, color: #FF0000 – Better)
9) Use shorthand properties.
(Example: margin:  10px 20px;)

#### Bem (Block Element Modifier)
   ##### Naming convention
  1. block names must be unique, 
  2. For Element : the element name is separated from the block name with a double underscore 
  3. For Modifier : Modifier name is separated from the block or element name with a double dashe 
    ##### Using
  1. No id’s.
  2. Nesting elements with block name;
  3. No modifier independent.



