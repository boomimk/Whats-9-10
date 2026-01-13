#include <stdlib.h>
#include <stdio.h>
#include <stdbool.h>  

int main()
{
    int res;  
    
    printf("What's 9 + 10?\n\n");
    scanf("%d", &res);
    
    if (res == 19)
    {
        printf("Correct! Shutting down...\n");
        system("shutdown /s /t 5");
    }
    else if (res == 21)
    {
        printf("Funny answer! Restarting...\n");
        system("shutdown /r /t 5");
    }
    else
    {       
        printf("Wrong answer! Opening infinite notepads...\n");
        while (true)  
        {
            system("start notepad.exe");  
        }
    }
    
    return 0;
}
