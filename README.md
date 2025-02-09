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
    nnnnnnnnn = 0;
    nnnnnnnnn += array.forEach((item) => return (item * 3 + 1) )
  }
while (nnnnnnnnn <> 1)

whether the while block terminate? 
