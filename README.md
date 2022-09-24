# pattern-question2
E
DE
CDE
BCDE
#include<iostream>
using namespace std;


int main() {
    
  int n;
    cin>>n;
    int i,j;
char c=65+n-1;
    char a;
    for(i=1;i<=n;i++){
for(j=0;j<i;j++){
a=c+j;
    cout<<a;}
    c--;
        cout<<endl;
    }
    
}
