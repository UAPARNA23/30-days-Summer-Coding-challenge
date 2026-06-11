1. problems: neither-minimum-nor-maximum

```java
class Solution {
    public int findNonMinOrMax(int[] nums) {
        int max = Integer.MIN_VALUE;
        int min = Integer.MAX_VALUE;
        for (int i = 0; i < nums.length; i++) {
            if (nums[i] > max) {
                max = nums[i];
            }
            if (nums[i] < min) {
                min = nums[i];
            }
        }
        for (int i = 0; i < nums.length; i++) {
            if (nums[i] != max && nums[i] != min) {
                return nums[i];
            }
        }

        return -1;
    }
}
```


2. problems:missing-number
```java
   class Solution {
    public int missingNumber(int[] nums) {
        int largest = nums[0];
        int m = nums.length;
        int exp = m*(m+1)/2;
        int actu = 0;
        for(int j=0;j<m;j++){
            actu = actu+nums[j];
        }
        int missing = exp - actu;
        return missing;
     }
   }
```

3. problems: find-the-duplicate-number
```java
class Solution {
    public int findDuplicate(int[] nums) {
        Arrays.sort(nums);
        for(int i=0;i<nums.length;i++){
            if(nums[i]==nums[i+1]){
                return nums[i];
            }
        }
        return 0;
    }
}
```

4. problems:find-numbers-with-even-number-of-digits

```java
class Solution {
    public int findNumbers(int[] nums) {
        int even_count =0;
       for(int i=0;i<nums.length;i++){
        int n = nums[i];
        int all_digit_count=0;
        while(n!=0){
            n = n/10;
            all_digit_count++;
        }
        if(all_digit_count % 2 ==0){
            even_count++;
        }
        }
        return even_count;
    }
}
```
