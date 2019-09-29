# Front-End-code-review
1)the number of spaces per indentation-level (2 spaces).
2)Print semicolons at the end of statements.
3)Print spaces between brackets in object literals. { key: “value” }
4)consistent spacing inside array brackets [ 1, 2 ]
5)Put the > of a multi-line JSX element at the end of the last line instead of being alone on the next line. 
Ex:<Component
    className="test"
    color="test"/>
6)consistent brace style for blocks function() {
	//your code
}
7)camelCase naming convention
8)capitalization of the first letter of a comment.
9)Remove unused imports/variables .
10)DRY. No duplication of code.
11)No unnecessary comments,Do not write comments for what you are doing, instead write comments on why you are doing.
12)Avoid multiple if/else blocks.(use switch instead)
13)Removed unused packages from NPM.
14)Use const over let (avoid var).
15)Use arrow functions instead of var that = this.
16)Use destructuring assignment for arrays and objects.
17)Use spread/rest operator.
18)Use default values.
19)Use template literals.
20)Use Promises or Asyns/Await. Rejection is handled.
21)Functional components for components that don't use state.(React)
22)No api calls in containers, delegate to Sagas
23)No state updates in loop.
24)No useless constructor.
25)Console has no any linter errors or warnings.
26)No console.logs.
27)A method should not be larger than 40 lines of code. The idea is, the function should be always viewable on a single screen without scrolling.
28)Place Scripts at the Bottom of Your Page
29)Avoid Globals : Global variables are a terribly bad idea
30)Your functions should do one thing only on one level of abstraction.
31)


