# code-3
#include<bits/stdc++.h>
using namespace std;

int dataTypeSize(string str) {
        
        cin>>str;
        
        if(str == "Character"){
            return 1;
        }
        if(str == "Integer"){
            return 4;
        }
        if(str == "Long"){
            return 8;
        }
        if(str == "Float"){
            return 4;
        }
        if(str == "Double"){
            return 8;
        }
    }
};
int main() {
    int t;
    cin >> t;
    while (t--) {
        string str;
        cin >> str;
        Solution ob;
        cout << ob.dataTypeSize(str);
        cout << "\n";
    }
    return 0;
