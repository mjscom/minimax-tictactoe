## Tic-Tac-Toe
The classic play-anywhere game, now versus the [Minimax AI](https://en.wikipedia.org/wiki/Minimax) 

#### Compile & Run
1. In terminal, `cd` to src/
2. Compile with `javac App.java logic/*.java model/*.java`
3. Run with `java com.project.tic.tac.toe.App`

#### Notes
* The UI allows a user to select their move using zero-indexed x, y coordinates. The top-most, middle cell would be (0, 1)
* The AI considers every remaining, legal move. Assuming the human player will play optimally - it assigns a score for the three end board states (win, loss, draw), and returns the highest
