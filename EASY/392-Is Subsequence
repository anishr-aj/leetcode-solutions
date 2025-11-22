class Solution {
    /**
     * Determines if string s is a subsequence of string t.
     * A subsequence is formed by deleting some (can be none) characters 
     * from t without changing the relative order of remaining characters.
     * 
     * @param s - The potential subsequence string
     * @param t - The target string to check against
     * @return true if s is a subsequence of t, false otherwise
     */
    public boolean isSubsequence(String s, String t) {
        // Get lengths of both strings
        int sLength = s.length();
        int tLength = t.length();
      
        // Initialize two pointers:
        // sPointer - tracks current position in string s
        // tPointer - tracks current position in string t
        int sPointer = 0;
        int tPointer = 0;
      
        // Iterate through both strings simultaneously
        while (sPointer < sLength && tPointer < tLength) {
            // If characters match, move pointer in s forward
            if (s.charAt(sPointer) == t.charAt(tPointer)) {
                sPointer++;
            }
            // Always move pointer in t forward
            tPointer++;
        }
      
        // If we've matched all characters in s, it's a subsequence
        return sPointer == sLength;
    }
}