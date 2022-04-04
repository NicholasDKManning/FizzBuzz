Nicholas Manning - March 4, 2022

FizzBuzz

Count from 1 to 100. Every number that's divisible by 3, print fizz. Every number that's divisible by 5, print buzz. Every number that's divisible by both, print fizzbuzz.

#include <stdio.h>

int main()

{
    
    int x;
    
    for(x = 1; x <= 100; x++)
    
    {
        
    if (x % 15 == 0)
        
        {
            
            printf("%d is divisible by both 3 and 5.  So -> fizzbuzz\n\n", x);
        
        }
        
    if (x % 5 == 0)
        
        {
            
            printf("%d is divisible by 5.  So -> buzz\n\n", x);
        
        }
        
    if (x % 3 == 0)
        
        {
            
            printf("%d is divisible by 3.  So -> fizz\n\n", x);
        
        }
        
    else 
    
    {
        
        printf("%d is not divisible by 5 or 3.\n\n", x);
        
    }
    
    }
    
    return 0;
    
}
