# <span style="color:red">**ARMSTRONG NUMBER**</span>
A positive integer of n-digits is called an Armstrong number if 

 <span style="color:blue">abcd……n-digits = a<sup>n</sup>+b<sup>n</sup>+c<sup>n</sup>+d<sup>n</sup>+…….
## <span style="color:red">**PSEUDOCODE**</span>
BEIGIN

INITIALIZE count=0

INITIALIZE sum=0

INPUT num

ASSIGN num=N, num=temp

WHILE N>0

           ASSIGN r = Nmod10       
           ASSIGN count = count+1
           ASSIGN N = N/10
END WHILE

WHILE num>0

           ASSIGN r = nummod10   
           ASSIGN sum = sum+power(r,count)
           ASSIGN num = num/10
END WHILE

IF temp = sum

      “It is a ARMSTRONG NUMBER”
ELSE

      “It is NOT a ARMSTRONG NUMBER”
END IF

END

## <span style="color:red">**FLOWCHART**


![ARMSTRONG NUMBER](https://user-images.githubusercontent.com/75233688/102039321-6f606b00-3def-11eb-9316-02696fddc776.jpeg)