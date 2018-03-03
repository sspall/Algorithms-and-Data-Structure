#include <stdio.h>
#define SIZE 1000
int input[SIZE];

int linear_search(int a[SIZE], int n, int num){
    int i;
    for(i=0;i<n;i++) {
        if(a[i] == num) {
            return 1;
        }
    }
    return 0;
}

int main(void) {
    int N, i, F;

    freopen("/home/sandeep/CLionProjects/untitled/input.txt","r",stdin);
    scanf("%d %d",&N, &F);
    for(i=0;i<N;i++) {
        scanf("%d",&input[i]);
    }
    printf("Element found = %d ", linear_search(input,N,F));
    return 0;
}
