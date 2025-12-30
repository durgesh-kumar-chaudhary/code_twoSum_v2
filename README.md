def two_sum(nums,target):
    for i in range(len(nums)):
        for j in range(i+1,len(nums)):
            if nums[i]+nums[j]==target:
                return [i,j]
    return -1 # -1 shows there is nothig any pair in which sum is equal to the target
nums=[1,6,4,5,3]
target=7
print(two_sum(nums,target))
            
                
            
