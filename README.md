# CPP MODULE 12 :

# 12a :

# PROGRAM STATEMENT :
Write a CPP Program to print the sorted elements of the Array.

# ALGORITHM :
1. Input Array: Read the number of elements and the array elements from the user.
2. Sorting: Use a sorting algorithm (e.g., std::sort from the C++ STL) to sort the array in 
ascending order.
3. Loop for Output: Use a loop to traverse through the sorted array.
4. Display Sorted Array: Print each element of the sorted array.
5. End Program: Output the sorted array and terminate the program.

# PROGRAM :
NAME : V>Kasivishvanath
REG NO : 212222040073
```
void print(int arr[])
{
 cout<<"After Sorting the Array: "<<endl;
 for (int i = 0; i < 5; i++)
 {
 cout<<arr[i]<<" ";
 }
 }
```

# OUTPUT:
 ![image](https://github.com/user-attachments/assets/02f7cc81-0671-4514-9c24-a547cdc8349b)

# RESULT :
Thus, The program is verified and executed successfully.The outputs match the expected 
results, confirming its correctness.

# 12b :

# PROGRAM STATEMENT :
Write the printArray module of Quick Sort in CPP.

# ALGORITHM :
1. Input Array: Accept an array of integers that needs to be sorted using the Quick Sort 
algorithm.
2. Partitioning: Define a function to partition the array around a pivot element, ensuring that 
elements smaller than the pivot go to the left and elements greater than the pivot go to the 
right.
3. Recursive Sorting: Recursively apply the Quick Sort algorithm to the subarrays on the left 
and right of the pivot.
4. Array Printing: In the printArray function, iterate through the array and print each element 
to display the sorted array.
5. End Program: After sorting, call the printArray function to display the final sorted array.

# PROGRAM :
```
Void printArray(int array[], int size)
{
 for(int i=0;i<size;i++)
 {
 cout<<array[i]<<" ";
 }
 cout<<endl;
 }
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/c4badf6c-b5cd-41f1-b431-f053e68d95e7)

# RESULT :
Thus, The program is verified and executed successfully.The outputs match the expected 
results, confirming its correctness.

# 12c :

# PROGRAM STATEMENT :
Write the mergeSort Module of Merge Sort in CPP

# ALGORITHM :
1. Divide the Array: Split the input array into two halves by finding the middle index.
2. Recursive Sorting: Recursively apply the mergeSort function to sort the left and right 
halves.
3. Merge the Halves: Merge the two sorted halves into a single sorted array by comparing the 
elements from each half.
4. Merge Function: Define a helper merge() function that merges two sorted subarrays into 
one sorted array.
5. Return Sorted Array: After merging, the array becomes sorted and is returned as the final 
output.

# PROGRAM :
```
void mergeSort(int arr[], int l, int r)
{
 if(l<r)
 {
 int m = l+(r-l)/2;
 mergeSort(arr,l,m);
 mergeSort(arr,m+1,r);
 merge(arr,l,m,r);
 }
 }
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/866d0a62-6f24-4be6-855e-98255478379a)

# RESULT :
Thus, The program is verified and executed successfully.The outputs match the expected 
results, confirming its correctness.

# 12d :

# PROGRAM STATEMENT :
Write the Element found module of Binary Search in CPP.

# ALGORITHM :
1. Input Array & Element: Accept the sorted array and the target element to search for.
2. Initialize Boundaries: Set the left boundary (low) to 0 and right boundary (high) to the size 
of the array minus one.
3. Binary Search Logic: While low <= high, calculate the middle index (mid) and compare the 
element at mid with the target element.
4. Element Found: If the element matches, return the index of the element (found); otherwise, 
adjust the boundaries (low or high) accordingly.
5. End Program: If the element is not found after checking all possibilities, return -1 indicating 
the element is absent.

# PROGRAM :
```
int ElementFound(int a[], int mid, int search)
{
 if(a[mid]==search)
 {
 cout<<"Element found at "<<mid+1<<" position";
 return 1;
 }
 else
 {
 return 0;
 }
}
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/c9f6313b-01c0-44ea-8920-e6875008bf7b)

# RESULT :
Thus, The program is verified and executed successfully.The outputs match the expected 
results, confirming its correctness.
