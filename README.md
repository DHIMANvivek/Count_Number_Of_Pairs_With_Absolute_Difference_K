# Count_Number_Of_Pairs_With_Absolute_Difference_K

# House-Robber

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->










#### Code you used for Submit/Run operation


```
// 2006. Count Number of Pairs With Absolute Difference K
class Solution {
    int count = 0 ;
    public int countKDifference(int[] nums, int k) {
        
        for(int i = 0 ; i<nums.length ;i++)
            for(int j=i+1 ; j<nums.length ; j++)
                
                if(Math.abs(nums[i]-nums[j])==k)
                  
                    count++;
                    
                
        return count;
              
        
    }
}
```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
this problem is based on two sum problem but new method is added - Math.abs()
Math.abs()
- In order to compute the absolute value for any number we do have a specified method in Java referred to as abs() present inside java.lang.Math class


#### Screenshots

![count number of pairs](https://user-images.githubusercontent.com/53940939/135705418-3f7bcb40-ef0f-4979-b4ba-023a5980ac36.png)






Thankyou :)
