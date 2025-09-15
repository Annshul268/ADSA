## 1. Two Sum
https://leetcode.com/submissions/detail/1670769567/

## Code
```java
class Solution {
    public int[] twoSum(int[] nums, int target) {
       for(int i = 0; i < nums.length ; i++){
            for(int j = i+1 ; j< nums.length ; j++){
                if(target == nums[i] + nums[j]){
                    return new int[]{i,j};
                } 
    }
}
