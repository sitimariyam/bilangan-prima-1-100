# bilangan-prima-1-100


    #include <iostream>
    #include <conio.h>
    using namespace std;

    int main(){
    int i,j,k;

    for(i=1;i<=100;i++){
        k=0;
        for(j=1;j<=i;j++){
            if(i%j==0){
                k+=1;
            }
        }
        if(k==2){
            cout<<i<<" ";
        }
    }
    getch();
    return 0;
   }
