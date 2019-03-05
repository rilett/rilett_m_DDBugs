# rilett_m_DDBugs
This project is about fixing the bugs that cause the puzzle to break. One of the bugs are when you complete the puzzle and try moving on to the next one, the background changes but the pictures from the last puzzle are still there and is difficult to put back on the left side.
How I would approach this is by looking at the script and reset code. If the pieces are not resetting with the image and the other pictures to left side then it must be related to that code. From the links provided it must be a parent/child node issue so fixing the problems in there would fix it.
