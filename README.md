# colltaz-conjecture
computational proof of colltaz conjecture

Colltaz Conjecture(1937) proposes this: any positive number following the transformation rule will eventually go to 1.
if (number is even) number /= 2
else number = number*3 + 1

idea: any positive number can be composed of
nnnnnnnnn = array [ppp + ppp + ppp + ppp]

do 
 
 if (nnnnnnnnn is even) nnnnnnnnnn/= 2 
 else {   
    let sum = 0;
    array.forEach(element => {
            element = element * 3 + 1;
            sum += element;
   });
   nnnnnnnn = sum;
  }
while (nnnnnnnnn <> 1)

whether the while block terminate? 
