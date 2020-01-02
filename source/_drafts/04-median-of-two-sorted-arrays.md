```java
class Solution {
    public double findMedianSortedArrays(int[] nums1, int[] nums2) {
        if (nums1 == null || nums1.length == 0) {
            //
            int size = nums2.length;
            if (size % 2 == 0) {
                return (num2[size / 2 - 1] + num2[size / 2]) / 2;
            } else {
                return num2[size / 2];
            }
            if (nums2 == null || nums2.length == 0) {
                //
                return 0.0;
            }
        } else if (nums2 == null || nums2.length == 0) {
            //
            int size = nums1.length;
            if (size % 2 == 0) {
                return (num1[size / 2 - 1] + num1[size / 2]) / 2;
            } else {
                return num1[size / 2];
            }
        } else {
            //
            int size = num1.length + num2.length;
            int nm1 = num1.length / 2;
            int nm2 = num2.length / 2;
            int cur = 0;
            int curNum = 0;

            if (nums1[0] > nums2[nums2.length - 1]) {
                //
            } else if (nums2[0] > nums1[nums1.length - 1]) {
                //
            } else {
                //
            }
        }
    }
    private double check(int[] nums1, int[] nums2, int size, int cur, int curNum) {
        if (size % 2 == 0) {
            //
        } else {
            //
        }
        int nm1 = num1.length / 2;
        int nm2 = num2.length / 2;
        if (num1[nm1] > num2[nm2]) {
            cur = nm2 - 1;
            curNum = num2[cur]
        }
    }
}
```