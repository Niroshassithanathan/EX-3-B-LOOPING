# EX-3-B-LOOPING
## AIM :
Create a C program to check whether the given number is Armstrong number or not. 
## ALGORITHAM :
1.Start.

2.Declare variables to store the input number (num), a variable to store the sum of cubes of digits (sum), and a temporary variable to store each digit (digit).

3.Prompt the user to enter an integer number and read it into the variable num.

4.Initialize sum to 0 (sum = 0).

5.Create a temporary copy of the original number (temp = num).

6.End.
## PROGRAM :
```
#include <stdio.h>
int main(){
int n,a=0,b=0,temp=0;
scanf("%d",&n);
temp=n;
while(n!=0)
{b=n%10;
a=a+(b*b*b);
n=n/10;
}
if(temp==0)
printf("%d is armstrong number",temp);
else
printf("%d is not a armstrong number",temp);
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-3-B-LOOPING/assets/121418437/f4756afe-6de3-45f8-b5eb-815fb6abf0fb)

## RESULT :
Thus , The C program has been executed successfully.

