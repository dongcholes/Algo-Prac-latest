## Problem Summary




## My solution

```java

class Solution {
    public int minimumSum(int num) {
        String[] arr = String.valueOf(num).split("");
        Arrays.sort(arr);
        int new1 = Integer.valueOf(arr[0] + arr[2]);
        int new2 = Integer.valueOf(arr[1] + arr[3]);
        
        return new1 + new2;
    }
}

```
<br><br>

## Other better Solutions
