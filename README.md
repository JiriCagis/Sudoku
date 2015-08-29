<h1> Sudoku 1.0 </H1>
Sudoku is logical numbers game for one player. 
The classic Sudoku game involves a grid of 81 squares. The grid is divided into nine blocks, 
each containing nine squares. The rules of the game are simple: each of the nine blocks has to
contain all the numbers 1-9 within its squares. Each number can only appear once in a row, column
or box. The difficulty lies in that each vertical nine-square column, or horizontal nine-square 
line across, within the larger square, must also contain the numbers 1-9, without repetition or omission.

<H3> Description Algorithm generate sudoku</H3>
 First initialize sequence numbers for filling fields.
 After recursive try put one number from sequence numbers and
 testing if number really belong to this field. Consecutive another 
 try put numbers. If not be put nothing number from sequence, algorithm
 return back to previous field and examine other number from sequence.
 In last step remove number from grid on random positions. Programmer can 
 set how much field will removed. Difficult sudoku is influence count field to remove.
 For example if will removed only 10 fields. Sudoku is very 
 easy for calculate that number assign to blank field.

<H3>Main function</H3>
- Sudoku is dynamic generate
- Different levels (beginner, classical and sudoku master)
- Verify correct after complete all fields in sudoku 
- Save game after close application and return game with again open application
- Window is dynamic stretchable
- Remember your position and size window

<H3>Technologie</H3>
- Programming language; Java 7
- Graphical interface: Swing
- Back-tracking: Generate numbers grid
- Persist data: XML format
- Unit testing: JUnit
