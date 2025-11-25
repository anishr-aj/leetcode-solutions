class Solution {
    public int maxArea(int[] height) {
        int leftPointer = 0;
        int rightPointer = height.length - 1;
        int maxAreaFound = 0;

        while (leftPointer < rightPointer) {
            int currentHeight = Math.min(height[leftPointer], height[rightPointer]);
            int currentWidth = rightPointer - leftPointer;
            int currentArea = currentHeight * currentWidth;

            maxAreaFound = Math.max(maxAreaFound, currentArea);

            if (height[leftPointer] < height[rightPointer]) {
                leftPointer++;
            } else {
                rightPointer--;
            }
        }

        return maxAreaFound;
    }
}
