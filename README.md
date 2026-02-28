class Solution:
    def reverseArray(self, arr):
        left = 0
        right = len(arr) - 1
        
        while left < right:
            arr[left], arr[right] = arr[right], arr[left]
            left += 1
            right -= 1
        
        return arr
<img width="1893" height="515" alt="Screenshot 2026-02-28 112628" src="https://github.com/user-attachments/assets/0862b9b7-a019-40e4-8a46-7a688edf94c9" />
