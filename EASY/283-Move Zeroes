class Solution {
    public void moveZeroes(int[] nums) {
        // Pointer to track the position where next non-zero element should be placed
        int nonZeroIndex = 0;
        int arrayLength = nums.length;
      
        // Iterate through the entire array
        for (int currentIndex = 0; currentIndex < arrayLength; currentIndex++) {
            // If current element is non-zero, swap it with element at nonZeroIndex position
            if (nums[currentIndex] != 0) {
                // Swap current non-zero element with element at nonZeroIndex
                int temp = nums[currentIndex];
                nums[currentIndex] = nums[nonZeroIndex];
                nums[nonZeroIndex] = temp;
              
                // Move nonZeroIndex pointer forward for next non-zero element
                nonZeroIndex++;
            }
        }
    }
}