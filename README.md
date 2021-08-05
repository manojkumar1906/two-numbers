#include<bits/stdc++.h>

using namespace std;

int main(){
    int T;
    cin>>T;
    int A[T],B[T],N[T];
    for(int i=0;i<T;i++){
        cin>>A[i]>>B[i]>>N[i];
    }

    for(int i=0;i<T;i++){
        if(N[i]%2==1){
            A[i]=A[i]*2;
        }
        cout<<max(A[i],B[i])/min(A[i],B[i])<<endl;
            
    }
    
}
