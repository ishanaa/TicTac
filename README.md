Dive into the nostalgic realm of Tic-Tac-Toe, thoughtfully implemented in the expressive Leo programming language.

Game Board Structure

In this implementation, Leo's versatile struct functionality takes center stage, meticulously crafting the game board. The Board struct is intricately composed of three Row elements. While other programming languages might leverage arrays for a similar purpose, Leo, at this juncture, does not support such structures.

Key Features of Leo Utilized

Several key features of the Leo programming language come into play:

Creation of Structures (struct): Leo's capacity to define structures is harnessed to architect the game board systematically.

Implementation of Conditional Logic: The game logic is seamlessly governed by conditional statements, ensuring the flow of the game adheres to the rules.

Function Exits Using Return: Functions are strategically designed to conclude with the 'return' statement, contributing to the clarity and efficiency of the code.

How to Run the Game

Navigating the game is facilitated through Leo's command line interface, streamlining the compilation and execution processes. Input can be seamlessly provided through the command line itself or extracted from an input file nested within the inputs/ directory.

Command Line Input

Executing the following command structure launches the game:
leo run <function_name> <input_1> <input_2> ...
For a more concrete example, refer to the ./run.sh script.

Input File

For those preferring an input file approach, modifications to inputs/tictactoe.in with the requisite inputs are necessary. Execution is then initiated using:
leo run <function_name>

Execution Command
leo execute <function_name> <input_1> <input_2> ...

Gameplay Instructions

Step 1: Initialize a New Board
leo run new

0    0    0
0    0    0
0    0    0
Step 2: Player 1's Move
leo run make_move 1u8 1u8 1u8 "{ r1: { c1: 0u8, c2: 0u8, c3: 0u8 }, r2: { c1: 0u8, c2: 0u8, c3: 0u8 }, r3: { c1: 0u8, c2: 0u8, c3: 0u8 } }"


1    0    0
0    0    0
0    0    0
Step 3: Player 2's Move
leo run make_move 2u8 2u8 2u8 "{ r1: { c1: 1u8, c2: 0u8, c3: 0u8 }, r2: { c1: 0u8, c2: 0u8, c3: 0u8 }, r3: { c1: 0u8, c2: 0u8, c3: 0u8 } }"


1    0    0
0    2    0
0    0    0
Enjoy the strategic maneuvering in Leo's rendition of the classic Tic-Tac-Toe game!
