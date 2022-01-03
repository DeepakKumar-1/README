# **DATA STRUCTURES**

**Arrays** <br />

# Searching <br />

### 1. Linear Search
* Linear search is also called as sequential search algorithm. 
* It is the simplest searching algorithm. In Linear search, we simply traverse the list completely and match each element of the list with the item whose location is to be found.
*[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/dbf6761db8ac24bfba67ae73f83e3cd252a11dc8/Linear%20Search)<br>*
*Time Complexity :*  <br />
   * Best Case :  `O(1)`   <br />
   * Worse Case : `O(n)`    <br />
   * Average Case : `O(n/2)`  <br />
  
  ![linear_search](https://user-images.githubusercontent.com/85002425/147288581-35cae12a-c960-4209-99a3-09b23872600e.gif)

    

**2. Binary Search** 

[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/main/Binary%20Search) 
![Binary Search](https://user-images.githubusercontent.com/85002425/147320726-232ac7c2-1874-448f-a806-f918bd8a607d.gif)

*Time Complexity :*  <br />
   * Best Case :  `O(1)`  <br />
   * Worse Case : `O(logn)`   <br />
   * Average Case : `O(logn)`    <br />

# Sorting

**Bubble Sort**

[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/main/Bubble%20Sort)

![bubbleSort](https://user-images.githubusercontent.com/85002425/147344877-0ba535fb-7099-47c1-8059-42a3f3343dc0.gif)

*Time Complexity :*  <br />
    Best Case :  O(n)    When Array is Already Sorted   <br />
    Worse Case : O(n^2)    <br />
    Average Case : O(n^2)  <br />

**Insertion Sort**

[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/main/Insertion%20Sort)

![Insertion Sort](https://user-images.githubusercontent.com/85002425/147346011-17b0ea20-bab7-4fc2-880d-bf62df263a69.gif)

*Time Complexity :*  <br />
    Best Case :  O(n)    When Array is Already Sorted   <br />
    Worse Case : O(n^2)    <br />
    Average Case : O(n^2)  <br />
    
**Selection Sort**

[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/main/Selection%20Sort)

![Selection Sort](https://user-images.githubusercontent.com/85002425/147348185-0210098a-7cce-473d-9c88-ce1e1cb0acd6.gif)

*Time Complexity :*  <br />
    Best Case :  O(n^2)  <br />
    Worse Case : O(n^2)    <br />
    Average Case : O(n^2)  <br />    
    
**Cyclic Sort**

[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/main/Cyclic%20Sort)

![cycle Sort](https://user-images.githubusercontent.com/85002425/147348970-dd41a2f6-f5fd-4c77-8546-9ee8c558e4df.jpg)

*Time Complexity :*  <br />
    Best Case :  O(n^2)  <br />
    Worse Case : O(n^2)    <br />
    Average Case : O(n^2)  <br />        
    
**Merge Sort**

[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/main/Merge%20Sort)

![Merge Sort](https://user-images.githubusercontent.com/85002425/147349715-16f292c4-603c-43cc-982a-aaaf8f3a1f61.gif)

*Time Complexity :*  <br />
    Best Case :  O(nlogn)  <br />
    Worse Case : O(nlogn)    <br />
    Average Case : O(nlogn)  <br />  
    
**Quick Sort**

[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/main/Quick%20Sort)

![Quick Sort](https://user-images.githubusercontent.com/85002425/147349707-21fd9cf3-80df-4e67-b4b5-611c8f9d6e17.gif)

*Time Complexity :*  <br />
    Best Case :  O(nlogn)  <br />
    Worse Case : O(n^2)    <br />
    Average Case : O(nlogn)  <br />  
    
**Count Sort**

[Code](https://github.com/DeepakKumar-1/DSA-In-JAVA/blob/main/Count%20Sort)

![Count Sort](https://user-images.githubusercontent.com/85002425/147350923-dd4017ae-2d1f-49e6-af19-a284d25f4fb9.gif)

*Time Complexity :*  <br />
    Best Case :  O(n+k)  <br />
    Worse Case : O(n+k)    <br />
    Average Case : O(n+k)  <br />    

# Heap Sort

![Heapsort-example](https://user-images.githubusercontent.com/85002425/147473589-4b1a9651-7079-4a56-bfc1-dcfec9e2fda0.gif)

*Time Complexity :*  <br />
    Best Case :  O(nlogn)  <br />
    Worse Case : O(nlogn)    <br />
    Average Case : O(nlogn)  <br /> 

# Linked Lists 
A _Linked List_ is a Linear Data Structure includes series of Connected Nodes, they are Linked with the help of pointers, Here Each Node has Data and Address Part  <br />
* ***Singly Linked List*** : Sequence of Nodes where Each Node Points to Next Node and Last Node Points to NULL <br />
* **_Doubly Linked List_** : Sequence of Nodes where each Node Contains Two Pointers prev(To point Previous Node) and Next(To point Next Node) and First as well Last Node of the Sequence Points to NULL  <br />
* **_Circular Linked List_** : Sequence of Nodes where each Node points to Next Node and Last Node Points back to the First Node of the Sequence  <br />
*Time Complexity :*  <br />
Traversal : O(n) <br /> 
Insertion : O(1)  <br /> 
Deletion : O(1) <br /> 
Search : O(n)     <br /> 
