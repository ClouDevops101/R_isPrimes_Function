# R_isPrimes_Function
Function that detect primes Number, Fibonacci and such staff
````R
    isPrimes <- function(n) {
      if ( (n %% 3) == 0 || (n %% 5) == 0  || (n %% 7) == 0 ) {
          print ("is not prime")
      } else {
          print ("is prime")
      }

  }
```
