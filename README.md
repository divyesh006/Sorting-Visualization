# Sorting-Visualization
This is a Java program that implements a visualization of different sorting algorithms. 
The program creates a window with buttons for each sorting algorithm and displays bars that represent elements of an array. The height of each bar is proportional to the value of the corresponding element in the array. The user can select a sorting algorithm and watch as the bars move to their sorted positions.

The program uses the Java Swing library to create the window and draw the bars. The class SortingVisualization extends the JPanel class and implements the ActionListener interface. The paintComponent method is overridden to draw the bars, and the actionPerformed method is implemented to handle button clicks. The program also includes methods to generate random data and implement various sorting algorithms: bubble sort, selection sort, insertion sort, and merge sort.

The generateRandomData method generates an array of random integers with a specified number of elements and maximum value.

The paintComponent method loops over the elements of the data array and draws a bar for each element using the fillRect method of the Graphics object.

The bubbleSort, selectionSort, and insertionSort methods implement the corresponding sorting algorithms and update the data array and repaint the panel after each comparison and swap operation.

The mergeSort method is a recursive implementation of the merge sort algorithm that calls the merge method to combine sorted subarrays.

Overall, the program provides a nice visualization of different sorting algorithms and can be used to demonstrate their behavior and efficiency. However, it has some limitations, such as a fixed window size and a limited number of elements that can be displayed. 

<h2>Bubble Sort</h2>

https://user-images.githubusercontent.com/81521224/226104759-f7154cd0-96cc-465d-8854-a52d2584c68d.mp4




