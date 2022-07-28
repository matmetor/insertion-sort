# insertion-sort

[22,27,16,2,18,6] % (n)  
[2,27,16,22,18,6] % (n-1)  
[2,6,16,22,18,27] % (n-2)  
[2,6,16,18,22,27] % (1)  

# big-O notation

n+(n-1)+(n-2)+1=n*(n+1)/2  
(n^2+n)/2=O(n^2)

# Time Complexity

After sorting the array from smallest to largest; [2,6,16,18,22,27]  
18 is in the middle of the array so time complexity considered as average case.

# First 4 steps of [7,3,5,8,2,9,4,15,6] array

[2,3,5,8,7,9,4,15,6]  
[2,3,5,8,7,9,4,15,6]  
[2,3,4,8,7,9,5,15,6]  
[2,3,4,5,7,9,8,15,6]  
