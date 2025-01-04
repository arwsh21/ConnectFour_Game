### Connect Four Game Overview  
Connect Four is a timeless two-player strategy game where players alternate turns dropping tokens into a vertical grid. The goal is to align four tokens horizontally, vertically, or diagonally before the opponent does. Its blend of simplicity and strategic depth makes it an excellent choice for exploring programming concepts. This project implements a basic console-based version of Connect Four, where players interact via a text-based interface.

---

### Game Logic  

#### Grid Size  
- The grid size is customizable, determined by user input at the start of the game.  
- Players can choose from grid dimensions of 4x4, 5x5, or 6x6, enabling adaptability to different grid sizes.  

#### Rules and Winning Conditions  
- Players alternate turns, selecting a column to drop their discs into.  
- The winning condition requires four consecutive discs in a horizontal, vertical, or diagonal line, regardless of the grid size.  

#### How Moves Are Processed  

**Grid Initialization**  
- The program dynamically allocates memory for the grid based on the user-selected dimensions.  
- Supported grid sizes include 4x4, 5x5, and 6x6.  

**Turn Logic**  
- Each player selects a column number (1 to the number of columns).  
- The program places the disc in the first available empty spot in the chosen column, starting from the bottom row and moving upward.  

**Win Check**  
- After each turn, the program evaluates the grid to determine if a player has achieved the winning condition (4 consecutive discs in any direction).  
- The win-checking mechanism remains consistent across all grid sizes, scanning for horizontal, vertical, and diagonal alignments.  

**End of Game**  
- The game concludes when a player successfully aligns four discs or when the grid is completely filled.  

This implementation provides a flexible, dynamic, and engaging way to enjoy Connect Four while showcasing fundamental programming techniques.
