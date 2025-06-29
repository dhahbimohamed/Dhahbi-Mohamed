# ✅ Day 3 - LeetCode - Valid Anagram
# 🔗 Link: https://leetcode.com/problems/valid-anagram/
# 🧠 What I learned:
# - How to compare two strings to check if they are anagrams
# - Using set and count to check character frequency

def isAnagram(s, t):
    # Anagrams must be the same length
    if len(s) != len(t):
        return False

    # For each unique character, check that both strings have the same count
    for char in set(s):
        if s.count(char) != t.count(char):
            return False

    return True

# 🧪 Example test cases
print(isAnagram("listen", "silent"))  # ✅ True
print(isAnagram("hello", "bello"))    # ❌ False
print(isAnagram("aabb", "bbaa"))      # ✅ True
print(isAnagram("rat", "car"))        # ❌ False
