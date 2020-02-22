#include <stdio.h>
void main()
{
    char string[80];
    int count, nc = 0, sum = 0;
 
    printf("Enter the string  \n");
    scanf("%s", string);
    for (count = 0; string[count] != '\0'; count++)
    {
        if ((string[count] >= '0') && (string[count] <= '9'))
        {
            nc += 1;
            sum += (string[count] - '0');
        }
    }
    printf("NO. of Digits in the string = %d\n", nc);
    printf("Sum of all digits = %d\n", sum);
}
output:-
Enter the string
num32ab67
NO. of Digits in the string = 4
Sum of all digits = 18

//solutions in java
import java.util.Scanner;

public class vowels {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the string:");
        String x= sc.nextLine();
        int sum = 0;
        for(int i = 0; i < x.length(); i++) {
            if(Character.isDigit(x.charAt(i))) {
                sum = sum + Integer.parseInt(x.charAt(i) + "");
            }
        }
        System.out.println(sum);
    }
}
output:-
Enter the string:
num32ab67
18
