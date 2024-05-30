# Backtracking Algorithm

Here, I use the backtracking algorithm as a brute-force technqiue to create a sudoku solver. 

I just used sudoku an an example of a constraint satisfaction problem (CSP). There are many ways to go about this but the backtracking algorithm is often used for CSP and consists of a brute-force technique which incrementally builds candidates to a solution and abandons them once it is apparent a candidate cannot be reasonably used to reach a satisfactory conclusion. 

This is the kind of pattern it follows in a state space tree: 
![image](https://user-images.githubusercontent.com/84393679/224001386-4a0c61ef-6b82-40b9-83f4-bbe35d6fb027.png)
