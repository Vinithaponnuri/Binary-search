class Solution:
    def search(self,a,s):
        n=len(a)
        for i in range(n):
            if a[i]==s:
                return i
        return -1
