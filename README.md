Home  Encyclopedia of Cryptography and Security  Reference work entry
RSA factoring challenge
Burt Kaliski 
Reference work entry
508 Accesses

Starting in 1991, RSA Data Security offered a set of “challenges” intended to measure the difficulty of integer factoring. The challenges consisted of a list of 41 RSA Numbers, each the product of two primes of approximately equal length, and another, larger list of Partition Numbers generated according to a recurrence.

The first five of the RSA Numbers, ranging from 100 to 140 decimal digits (330–463 bits), were factored successfully by 1999 (see [2] for details on the largest of these). An additional 512-bit (155-digit) challenge number was later added in view of the popularity of that key size in practice; it was also factored in 1999 [1].

In addition to the formal challenge numbers, an old challenge number first published in August 1977, renamed ‘RSA-129’, was factored in 1994 [1].

The Quadratic Sieve was employed for the numbers up to RSA-129, and the Number Field Sieve for the rest.
