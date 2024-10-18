#include <bits/stdc++.h>

using namespace std;
int camelcase(string s) {
    int count=0;
    for(int i=0;i<s.size();i++){
        if(s[i]>=65 && s[i]<=90){
        count++;
        }
    }
    return count+1;

}
int main()
{
    ofstream fout(getenv("OUTPUT_PATH"));

    string s;
    getline(cin, s);

    int result = camelcase(s);

    fout << result << "\n";

    fout.close();

    return 0;
}
