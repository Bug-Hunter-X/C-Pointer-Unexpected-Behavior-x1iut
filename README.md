# C Pointer Unexpected Behavior

This repository demonstrates a common C programming error related to pointer manipulation. The `bug.c` file contains code that exhibits unexpected behavior when modifying memory locations pointed to by pointers. The `bugSolution.c` file provides a corrected implementation that avoids this issue.  The bug stems from assuming that modifying the value pointed to by a pointer directly affects the original variable when the pointer's target is changed. 

This is an educational example to highlight the importance of understanding how pointers work and how modifications impact memory directly rather than indirectly.