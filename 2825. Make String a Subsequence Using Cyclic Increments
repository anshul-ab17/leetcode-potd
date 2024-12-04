class Solution {
public:
    bool canMakeSubsequence(string str1, string str2) {
        int j = 0;
        int n1 = str1.size(), n2 = str2.size();
        
        for (int i = 0; i < n1 && j < n2; ++i) {
            if (str1[i] == str2[j] || (str1[i] - 'a' + 1) % 26 + 'a' == str2[j]) {
                ++j;
            }
        }
        
        return j == n2;
    }
};
