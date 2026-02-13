# DSA-Batch-4
# Two Sum


class Solution {

    public int[] twoSum(int[] nums, int target) {
    int[] ans=new int[2];
    int n=nums.length;
    for(int i=0;i<n;i++)
    {
        for(int j=i+1;j<n;j++)
        {
            if(target==(nums[i]+nums[j]))
            {
                ans[0]=i;
                ans[1]=j;
                return ans;
            }
        }
    }
    return ans;

    }
}
