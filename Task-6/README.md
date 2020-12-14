![task 6 flowchart-page0001 (1)](https://user-images.githubusercontent.com/75221857/102055998-8af05500-3da0-11eb-9973-176a1f64b1e7.jpg)
The above is flowchart to check weather a number is Armstrong number or not .
I an new to programming and all so i just wrote what ever i know and learnt from my PSAT lab class.can you please excuse me if i am wrong.

Pseudocode:

READ number

number=n

sum=0

WHILE number>=0
   sum=sum+ (number%10)*  (number%10) * (number%10)

   number=number/10

ENDWHILE

IF sum==number

    ECHO "given number is an armstrong number"

ELSE

    ECHO "given number is not an armstrong number" 