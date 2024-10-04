int num = 251025,rem =0,sum=0,temp;
temp = num;
here we are giving the intial values 
and we are storing the num value in temp;
while(num>0){
if num value is greater than 0 then enter into the loop 
rem =num%10;
the num value will be divided by 10 then the remainder will be stored in rem
sum = sum + rem ;
the remainder value will be added to the sum value;
num = num/10;
you will get the remaining number
logic:
while (num>0){ ---- if the num value is greater than 0 then enter into the loop 
rem =num%10; ------ divide num value by 10 store value in rem;
sum = sum + rem;
num = num/10
step 1:
250125>0
so enter into loop 
250125%10 = 5 
rem =5;
sum = 0+5;
sum = 5;
250125/10 25012
step 2 :
25012>0
25012%10 =2
rem =2;
sum = 5+2;
sum = 7;
25012/10 = 2501;
step3:
2501>0
2501%10 =1 
rem = 1
sum = 7+1 =8;
2501/10 = 250;
step4:
250>0
250%10 =0 
sum = 8+0;
250/10 =25
step 5:
25>0
25%10 = 5
rem = 5;
sum = 8+5 = 13;
25/10 = 2 ;
step 6:
2>0
2%10 = 2
sum =13+2 =15 
