# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common error in Java programming: the `ArrayIndexOutOfBoundsException`. The bug arises from attempting to access an array element using an index that is out of bounds.

## Description

The provided Java code creates an integer array of size 5 and then attempts to assign values to indices 0 through 5 in a for loop. However, valid array indices range from 0 to 4.  Accessing `arr[5]` results in an `ArrayIndexOutOfBoundsException`. 

## Solution

The solution corrects the for loop condition to iterate up to, but not including, `arr.length`. This prevents the out-of-bounds access. The corrected code safely populates the array.