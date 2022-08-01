# Arrays Explained

<img src="#" alt="JS Array Sample">

<p>An array is a group of related data elements saved in neighboring memory locations. 
This standard data structure contains every data element that can be entered as soon as possible by just using its index number. </p>

<p>For example, Angie can create an array as a shopping list for the grocery store. Angie can code it where she can make a variable for the array, followed by an assignment operator, and then the brackets with the array objects: apples, and cucumbers.

    const shopping list = ['apple', 'cucumbers']; 

</p>

<h3>Prefix List Sample in Python: Running Sum of 1D Array</h3>

<p>

    class ArraySoln: # step 1
        def answers(self, nums): # step 2
            for k in range(1, len(nums)): # step 3
                nums[k] += nums[k - 1] # step 4
            return nums # last step
</p>

<h3>Scenario with Solution</h3>
<p>Suppose Angie wanted a list called answers to help her add a different set of numbers automatically. This answers list will return the sum of numbers. First, Angie will create a class and then a function, answers, to store her variables, decision making, and the return statement. The idea here is to contain parameters self, nums, and integer list loop through all of the possible sets of numbers that will be added and return this sum of answers list. Next, Angie will rise the index of k by the last index's answers sum. In this case, the last index's sum is saved at the index k - 1 inside the stored list. This process is repeated again because all of the indexes will loop through 1 to k - 1. In terms of time complexity, it will be O(n) because k represents the length of the list's input. Lastly, for space complexity, it will be O(1) because no extra space was used to discover the answer's sum. At the same time, she did not think about the space involved in the result answer list. </p>


