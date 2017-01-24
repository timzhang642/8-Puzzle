# 8-Puzzle
### The following searach algorithms are implemented:
* Breadth-first search
* Depth-first search
* Iterative deepening DFS search
* Uniform-Cost search
* Best-first search, h = number of tiles that are not it correct position
* A*1 search, h = number of tiles that are not it correct position
* A*2 search, h = sum of Manhattan distances between all tiles and their correct positions
* A*3 search, h = fair Manhattan distance

### Example:
Initial state<br>
[1 2 3]<br>
 [8 6 4]<br>
 [7 5 0]<br>
action= None , depth= 0 <br>

step 1<br>
[1 2 3]<br>
 [8 6 4]<br>
 [7 0 5]<br>
action= move 5 to the right , depth= 1 <br>

step 2<br>
[1 2 3]<br>
 [8 0 4]<br>
 [7 6 5]<br>
action= move 6 down , depth= 2. Goal state found
