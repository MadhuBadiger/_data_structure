# _data_structure
Algorithms
#algorithm for prime number
Step 1: Start
Step 2: Initialize variables num,flag=1, j=2
Step 3: Read num from user
Step 4: If num<=1            // Any number less than 1 is not a prime number
            Display "num is not a prime number"
            Goto step 7
Step 5: Repeat the steps until j<[(n/2)+1]
            5.1 If remainder of number divide j equals to 0,
                    Set flag=0
                    Goto step 6
            5.2 j=j+1
Step 6: If flag==0,
            Display num+" is not prime number"
        Else 
            Display num+" n is prime number"
Step 7: Stop
