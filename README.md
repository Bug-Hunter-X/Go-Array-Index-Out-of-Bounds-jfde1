# Go Array Index Out of Bounds
This example demonstrates a common error in Go: accessing an array index that is out of bounds.  The loop attempts to access `a[10]`, which is beyond the array's valid index range (0-9). This results in a runtime panic.

The solution shows how to correct the loop condition to prevent the out-of-bounds access.