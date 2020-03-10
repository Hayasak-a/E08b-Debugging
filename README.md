# E08b-Debugging

As usual, Fork and Clone this repository.

This exercise is an opportunity for you to debug syntax, interpreter, and other runtime errors in a fairly-complex project. Some of the syntax and concepts represented in this code may seem foreign or advanced, but if you work systematically, you should be able to address the problems in this code.

This exercise was adapted from the excellent platformer tutorial developed by GDQuest. Once you have corrected the problems, I hope this will provide a starting place for your project (if you have been struggling to get started).

I have introduced eight errors (of different types) into the scripts in this project. Your assignment is to find and correct those errors. Some of them are syntax or interpreter errors, which will prevent the program from running at all. Others are runtime or behavioral errors which may require a little more work to find.

The project is associated with a tutorial (both a free and paid version). The free version is in two parts and is available here:
 * [Make Your First 2D Game with Godot: Player and Enemy (beginner tutorial part 1)](https://www.youtube.com/watch?v=Mc13Z2gboEk)
 * [Make Your First 2D Game with Godot: Coins, Portals, and Levels (beginner tutorial part 2)](https://www.youtube.com/watch?v=6ziIyx60N6I)

The original source code is available on GitHub, but please only use it as a point of comparison after you have exhausted all other options.

When you have found all eight errors (one of them is on multiple lines), commit your changes, and turn in the URL of your repository on Canvas.

1. function to set deaths used "new_score" in its body rather than "new_value" like the parameter
2. teleport() had an incorrect indent on two lines
3. update_interface() used Text where it shoul dhave been text
4. get_direction() checked inputs for "Move_right" where the input map had "move_right"
5. set_score() set score to 5 after updating the score for no reason
6. EndScreen.gd refers to Score rather than score
7. Enemy sprite toggled to invisible
8. Enemies fly
9. (UNFIXED, because I can't identify where the sidescrolling function is, and the other 8 are more clearly intended bugs so the current submission should have all the intended ones): player is able to reach inescapable parts of the map that are also not scrolled to by heading to the very right of level 2
