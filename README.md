# PrimesCDD
Prime Numbers Concurrency Project

# Project Brief

 Concurrency ProjectPrime NumbersThere are an infinite number of prime numbers. Amongst the primes thereare what are known as twin primes.

  A twin prime is a prime number that is either 2 less or 2 more thananother prime number—for example, either member of the twin prime pair(41, 43). In other words, a twin prime is a prime that has a prime gap of two. Sometimes the term twin prime is used for a pair of twin primes; analternative name for this is prime twin or prime pair.
  It is (currently) unknown whether there are an infinite number of twinprimes. Examples include: (3, 5), (5, 7), (11, 13), (17, 19), (29, 31), (41,43),...
  
  Your task is to write a parallel program that counts the number of primesless thannfor any numbernand also finds and lists all twin primes less than. The code should run on linux.
  Example output after running your code withn=50would be:
  >primeTwinCount 50
  >Total number of primes: 15
  >Twin Primes: 3, 5, 7, 11, 13, 17, 19, 29, 31, 41, 43
  >
  You must submit the following:
  Source CodeFull source code including README, 
  full installation in-structions, 
  Makefile and Doxygen Configuration file;
  
  Report
  A short report on the approach you took to achieving maximumconcurrency. 
    This will contain:
      PseudocodeOutline of the algorithm illustrated with pseudocode;
      Speedup Results
      Bothabsolute speedup and relative speed up should be calculated
      ScalabilityGraph(s) showing the scalabiltiy of your code.
The report does not need to be long. It must be concise and on point.The idea is that you learn how to measure code performance as well aswrite parallel code. There is plenty of scope for making the code eﬀicient.
