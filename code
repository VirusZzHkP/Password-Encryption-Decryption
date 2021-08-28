#include <stdio.h>
#include<string.h>

void encrypt(int option,int key)
    {
        int i, len=0;
        char password[200];
        printf("\n\t\t\tEnter your password:");
        scanf("%s",password);
 
        len = strlen(password);
        printf("\n\t\t\tYour encrypted password is: ");
        
        
        for(i=0; (i<len&& password[i] != '\0'); i++)
        printf("%c",password[i]+key);
    }
void decrypt(int option,int key)
    {   
        int i, len=0;
        char password[200];
        printf("\n\t\t\tEnter your encrypted password:");
        scanf("%s",password);
 
        len = strlen(password);
        printf("\n\t\t\tYour decrypted password is: ");
 
        for(i=0; (i<len && password[i] != '\0'); i++)
        printf("%c",password[i]-key);
    }
    
int main()
{
    int option;
    char ch;
    print:
    printf("\t\t\tChoose Your Option\n\t\t\t1.ENCRYPTION\n\t\t\t2.DECRYPTION\n\n");
    scanf("%d",&option);
    if(option==1)
    encrypt(option,0XAED);
    else if(option==2)
    decrypt(option,0XAED);
    else
    printf("Please Choose Your Option Correctly!");
    again:
    printf ("\n\t\t\tDo you want to repeat the operation(Y/N): ");
    scanf (" %s", &ch);

    if(ch == 'y' || ch == 'Y'){
        goto print;
    }
    else if(ch == 'n' || ch == 'N'){
        return 0;
    }
    else{
        printf("\n\t\t\tPlease enter Yes or NO.\n");
        goto again;
    }
    return 0;
}
    

