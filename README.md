# Fenwick Tree Project

1. In order to run my project , first declare an array by making an object.
   Example: array=[1,2,3,4,5,6]
   
2. Now, make another object and call the "construct" function. That will make a binary indexed tree of the array.
   Example: bin_tree=construct(array,len(array))
   
3. You can print "bin_tree" to see the binary indexed tree

4. To find a sum of the array you initiaze, just call the getSum function and give the binary tree as a parameter and a range to find the    prefix sum of the given range.
   NOTE: IT GIVES THE PREFIX SUM OF THE ARRAY YOU INITIALIZE NOT OF THE BINARY TREE. BINARY TREE IS THERE JUST TO HELP YOU FIND THE PREFIX          SUM OF THE ARRAY WITH LESS COMPLEXITY!!!

   Example: print(getSum(bin_tree,3)) #That will give you 10
   
5. 
