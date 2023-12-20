Possible links to help with proving algorithm correctness: 
https://course.ccs.neu.edu/cs5002f18-seattle/lects/cs5002_lect11_fall18_notes.pdf
## Bubble sort
- A naïve approach to sorting any comparable values in a list.
Python code snippet:
```python
def bubblesort(arr):
	for i in range(len(arr)) #For each element of array
		for j in range(len(arr)-1) #Go through entire array
			if arr[j] < arr[j+1]: # Find maximal element and swap
				temp = arr[j]
				arr[j] = arr[j + 1]
				arr[j + 1] = temp
```
Pseudocode:
```
For j in :
	Loop through entire list:
		Find maximal element and move to the 
```
Time Complexity: $O(n^2)$

Proof of correctness (Check):
Proof of time complexity:

Bonus: Proof of space complexity?
## Insertion sort


Proof of correctness (Check):
Proof of time complexity:

Bonus: Proof of space complexity?
## Quick sort


Proof of correctness (Check):
Proof of time complexity:

Bonus: Proof of space complexity?
## Merge sort


Proof of correctness (Check):
Proof of time complexity:

Bonus: Proof of space complexity?
## Radix sort


Proof of correctness (Check):
Proof of time complexity:

Bonus: Proof of space complexity?
