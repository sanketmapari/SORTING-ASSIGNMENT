class Solution:
    def sortEvenOdd(self, nums: List[int]) -> List[int]:
        even = []
        odd = []
        result = []
        for i in range(len(nums)):
            if i % 2 == 0:
                even.append(nums[i])
            else:
                odd.append(nums[i])
        even.sort()
        odd.sort(reverse=True)
        for i,j in zip(even,odd):
            result.append(i)
            result.append(j)
        if len(even) > len(odd):
            result.append(even[-1])
        if len(odd) > len(even):
            result.append(odd[-1])
        return result
