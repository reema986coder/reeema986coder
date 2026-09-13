#include <stdio.h>
void traversal(int arr[], int n){
    
    for(int i = 0; i<5; i++){
        printf("%d\n", arr[i]);
    }
}
int main() {
    int arr[5]={ 5, 6 , 7, 4, 8};
     traversal( arr, 5);
    return 0;
}
