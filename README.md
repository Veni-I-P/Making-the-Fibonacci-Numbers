#include <stdio.h>

int main() {

    int num_1 = 0;
    int num_2 = 1;
    
    printf("%i\n", num_1);
    printf("%i\n", num_1 );

    int next_num = num_1 + num_2;


    while (num_1 < 1000) {
       
        printf("%i\n", next_num);
    
        int num_1 = num_2;
        int num_2 = next_num;
        int next_num = num_1 + num_2;
        }
    
    return 0;
}
