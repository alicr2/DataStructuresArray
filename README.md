README
This repository contains a simple Java implementation of a dynamic array.
 The Array class provides basic functionality for array manipulation, including insertion, removal, searching,
 and printing of elements.
 The implementation dynamically resizes the array as needed to accommodate additional elements.

Class:
 Array -represents the dynamic array and includes methods to manipulate the array
 Main- cotains the main method for testing the array class

 Array class is responsible for managing integer arrays using constructors ( public Array(int length)) to intialize the
 array with the specified length
 insert (public void insert (int item)) is used to add items ot the array if the array is full it creates a new array with
 double the capacity and copies the existing items to the new array
 removeAt (public void removeAt(int index)) removes and item at the specified index. if the index is invalid it throws
 an 'IllegalArgumentExpectation'
 indexOf (public int indexOf(int item)) searches for the item in the arrya and returns its index. If the item is not found
 it returns -1
 Print prints all the items in the array

 In the main class
 the main methods creates and array object, inserts  several items into the array, searches for and item, and prints the
 array.

 USAGE:
