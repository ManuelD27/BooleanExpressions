# BooleanExpressions

*
>   Greater than
<   Less than
==  Equal to
>=  Greater than equal to
<=  Less than equal to
!=  Not equal to
*/

#include <stdio.h>
#include <stdbool.h>

int main() {
    
    bool value1 = 32 > 30;
    bool value2 = 30 < 32;
    bool value3 = 35 == 35;
    bool value4 = 35 != 90;
    bool value5 = 9 >= 6;
    bool value6 = 9 <= 6;
    
    printf("%d\n", value1);
    printf("%d\n", value2);
    printf("%d\n", value3);
    printf("%d\n", value4);
    printf("%d\n", value5);
    printf("%d\n", value6);

    return 0;
}
