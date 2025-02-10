# data-visualisation
The human brain can easily process visuals in spite of long codes to understand the algorithms. In this article, Selection Sort visualization has been implemented using graphics.h library. As we all know selection sort first finds the minimum element from the unsorted array and swaps it with the first element of the unsorted array in each pass. It becomes difficult to analyze the data manually between two algorithms or vice versa, but plotting graphically it is much easier to understand.

Approach:

The white line is used to represent the length of number (9 being represented by 9 pixels vertically upwards) while its position represents its index in the array.
Graphical representation of randomly distributed numbers is shown below.
Graphically sorting can be shown by first coloring the minimum element from unsorted array as green color.
Now swap it with the first element of unsorted array and also swap the color for those two number as shown in code by swap_colors() function.
Here delay() can be increased to see the transition in the graph.



Pre-defined Functions Used:

setcurrentwindow(): A function which is used to set the size of current window.
setcolor(n): A function which is used to change the color of cursor by changing the value of n.
delay(n): A function which is used to delay the program by n milliseconds. It is being used for slowing down the transitions speed
line(x1, y1, x2, y2): A function which is used to draw an line from point (x1, y1) to point (x2, y2). (0, 0) being the left top corner of the screen and bottom right be (n1, n2) where n1, n2 are the width and height of the current window. There are other graphics which can be applied to this line using setcolor().
