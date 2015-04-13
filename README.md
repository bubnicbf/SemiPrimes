# SemiPrimes
determines whether a given number is semiprime, the product of two prime numbers

In mathematics, a semiprime (also called biprime or 2-almost prime, or pq number) is a natural number that is the product of two (not necessarily distinct) prime numbers. The semiprimes less than 100 are 4, 6, 9, 10, 14, 15, 21, 22, 25, 26, 33, 34, 35, 38, 39, 46, 49, 51, 55, 57, 58, 62, 65, 69, 74, 77, 82, 85, 86, 87, 91, 93, 94, and 95. 

By definition, semiprime numbers have no composite factors other than themselves. For example, the number 87 is semiprime and its only factors are 1, 3, 29, and 87.

Semiprimes are highly useful in the area of cryptography and number theory, most notably in public key cryptography, where they are used by RSA and pseudorandom number generators such as Blum Blum Shub. These methods rely on the fact that finding two large primes and multiplying them together (resulting in a semiprime) is computationally simple, whereas finding the original factors appears to be difficult. In the RSA Factoring Challenge, RSA Security offered prizes for the factoring of specific large semiprimes and several prizes were awarded. The most recent such challenge closed in 2007.

In practical cryptography, it is not sufficient to choose just any semiprime; a good number must evade a number of well-known special-purpose algorithms that can factor numbers of certain form. The factors p and q of n should both be very large, around the same order of magnitude as the square root of n; this makes trial division and Pollard's rho algorithm impractical. At the same time they should not be too close together, or else the number can be quickly factored by Fermat's factorization method. The number may also be chosen so that none of p − 1, p + 1, q − 1, or q + 1 are smooth numbers, protecting against Pollard's p − 1 algorithm or Williams' p + 1 algorithm. However, these checks cannot take future algorithms or secret algorithms into account, introducing the possibility that numbers in use today may be broken by special-purpose algorithms.

In 1974 the Arecibo message was sent with a radio signal aimed at a star cluster. It consisted of 1679 binary digits intended to be interpreted as a 23×73 bitmap image. The number 1679 = 23×73 was chosen because it is a semiprime and therefore can only be broken down into 23 rows and 73 columns, or 73 rows and 23 columns.
