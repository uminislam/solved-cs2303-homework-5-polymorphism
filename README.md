Download Link: https://assignmentchef.com/product/solved-cs2303-homework-5-polymorphism
<br>
<span class="kksr-muted">Rate this product</span>

Homework 5

The objective is to give you practice using polymorphism, with con- structing and destructing instances of classes.

The context of this problem is the game of checkers. In checkers, there aretwo kinds of pieces, pawns and kings; there are rules about how pawns can move,and how kings can move. When a pawn has advanced to the furthest row, itceases to be a pawn, and is replaced by a king. Rules for playing can be viewed at https://www.thesprucecrafts.com/play-checkers-using-standard-rules-409287. The program must, given an arrangement of pieces on the board, figure out thepossible moves, and (possibly randomly) choose one of the possible moves, gen-erating a new board configuration, unless there are no possible moves. If thereare no possible moves, this must be reported. In effect the program takes on therole of both players, one at a time. The game should proceed for a given numberof moves, unless a no move situation occurs. If a pawn reaches the furthest row,it must be crowned a king; after this the greater number of possible moves towhich it is entitled must be considered. If a pawn is captured, its instance mustbe destructed at the time of capture.

Note that the king can do everything a pawn can do. If we needed to substitute a king in, to carry out the role of a pawn, the king would be able to do so. Using the Liskov Substitutability Principle, we see that the king is-a-kind-of pawn (with additional powers).

Be sure to construct test cases for each function you build. Put thought into the test cases. The goal is to know that a function works, when it passes all of its test cases. One test case per function is usually not enough.

<ul>

 <li>Construct a sequence diagram for your project. You can draw it by hand and include a phone/photo, or draw it with a software tool.</li>

 <li>Use the test-driven development style for developing your code. Docu- ment this by taking a new screen shot of your test code every time you make a new test (See Figure 1.), and of your production code every time you extend your production code. It could be a large number of screen shots. Be sure to run your code every time you add a few lines of test or production code. (See Figures 2 and 3.) Do not allow the number of errors to get large.1</li>

</ul>

Figure 1: In the process of creating a new test.

Figure 2: Starting some production code.

Figure 3: Adding more production code.

2

<ul>

 <li>The program must display the configuration of the board after each move.</li>

 <li>The program must record the number of possible moves, the chosen move, and successive board configurations for each turn in a log file. You can choose the file format, but you must document that, and adhere to what you describe.Things to do:

  <ol>

   <li>Either:(a) Make a C++ project from the Hello,World project.(b) Populate that project with at least one class for Test, and at least one class for Production, as well as at least one include file for tests and at least one include file for production.or use the starter code.</li>

   <li>Create the sequence diagram and include the electronic file (diagram, screenshot or photo). Make sure your name appears within the sequence diagram.</li>

   <li>Place function prototypes for all of your functions from the sequence dia- gram into one or more .h files.</li>

   <li>As you work on the assignment, collect a sequence of screen shots showing how your test code, and your production code are growing.</li>

   <li>Be sure to build and run often; do not allow errors to build up.</li>

   <li>Show the sequence of game board configurations, and the number of pos- sible moves from each configuration.</li>

   <li>Receive the values entered on the command line. Ask for values not pro- vided in the command line. In either case, check for reasonable values. Negative number of turns implies no game should be conducted. Use these limit values in execution.</li>

  </ol></li>

</ul>