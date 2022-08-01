# Arrays Explained

<p>An array is a group of related data elements saved in neighboring memory locations. 
This standard data structure contains every data element that can be entered as soon as possible by just using its index number. </p>

<p>For example, Angie can create an array as a shopping list for the grocery store. Angie can code it where she can make a variable for the array, followed by an assignment operator, and then the brackets with the array objects: apples, and cucumbers.

    const shopping list = ['apple', 'cucumbers']; 

</p>

<h3>Prefix List Sample in Python: Running Sum of 1D Array</h3>

<code>

    class ArraySoln: # step 1
        def answers(self, nums): # step 2
            for k in range(1,len(nums)): # step 3
                nums[k] += nums[k - 1] # step 4
            return nums # last step
</code>

<h3>Scenario with Solution</h3>
<p>Suppose Angie wanted a list called answers to help her add a different set of numbers automatically. This answers list will return the sum of numbers. First, Angie will create a class and then a function, ArraySoln, to store her variables, decision making, and the return statement. The idea here is to contain parameters self, nums, and integer list loop through all of the possible sets of numbers that will be added and return this sum of ArraySoln. Next, Angie will rise the index of k by the last index's ArraySoln. In this case, the last index's sum is saved at the index k - 1 inside the stored list. This process is repeated again because all of the indexes will loop through 1 to k - 1. In terms of time complexity, it will be O(n) because k represents the length of the list's input. Lastly, for space complexity, it will be O(1) because no extra space was used to discover the ArraySoln's sum. At the same time, she did not think about the space involved in the result ArraySoln list. </p>


<h3>One-liner solution: return statement with for in range loop</h3>

<img src="https://github.com/angieintech/my-ds-a-notes/blob/main/Arrays/Python%20One-Liner.png" height="90px" length="90px" alt="pythonList"/>

<p>This one-liner solution will save more space and will be faster to run. It will do the same process. Instead of manually putting the beginning element, 1, in the for loop, we can use:k + 1 and have it add one each time but goes through the range of the length of numbers. </p>
