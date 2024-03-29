# README

<p align="justify">The program prints the prime numbers in a given range from 0 to n. The number separator in the output is a simple space.</p>

## Motivation

<p align="justify">Motivation was to writing a simple program for calculating prime numbers which are printed in one line without a trailing line break. The program is intended to work as simple generator of prime numbers for other scripts. For prime numbers less than 100000 the underlying algorithms is fast enough.</p>

## Pseudo Code

<p align="justify">Underlying algorithm as pseudo code</p>

    Data: Integer number n
    Output: Prime numbers smaller than n
    Function: prime_numbers
        A ← array of size n with boolean values set to true
        for i ← 2 to √n do
            if A[i] is true then
                j ← i * i
                while j ≤ n do
                    A[j] ← false
                    j ← j + 1
                end
            end
        end    
        return array with prime numbers and composite numbers
    end
    
## Output format

<p align="justify">A simple call looks like:</p>

    hades@hades:~$ prime_numbers
    hades@hades:~$ 2 3 5 7 11 13 17 19 23 29 31 37 41 43 47 53 59 61 67 71 73 79 83 89 97hades@hades:~$

<p align="justify">Without given boundary prime_numbers print the primes in a range of 0 to 100.</p>   

<p align="justify">A call with a boundary looks like:</p>

    hades@hades:~$ prime_numbers 1000
    hades@hades:~$2 3 5 7 11 13 17 19 23 29 31 37 41 43 47 53 59 61 67 71 73 79 83 89 97 101 103 107 
    109 113 127 131 137 139 149 151 157 163 167 173 179 181 191 193 197 199 211 223 227 229 233 239
    241 251 257 263 269 271 277 281 283 293 307 311 313 317 331 337 347 349 353 359 367 373 379 383 
    389 397 401 409 419 421 431 433 439 443 449 457 461 463 467 479 487 491 499 503 509 521 523 541 
    547 557 563 569 571 577 587 593 599 601 607 613 617 619 631 641 643 647 653 659 661 673 677 683 
    691 701 709 719 727 733 739 743 751 757 761 769 773 787 797 809 811 821 823 827 829 839 853 857 
    859 863 877 881 883 887 907 911 919 929 937 941 947 953 967 971 977 983 991 997hades@hades:~$ 

<p align="justify">The prime numbers in a range of 0 to 1000 are printed without line break.</p>

## Outstanding issues

<p align="justify">Writing this program I had in mind to compare the results from Bash with other programming languages like Python and C/C++. Open issue is the question how the memory managment can be optimised. It is also of interest how the calculation time can be reduced by change of the programming language and by modifying the code.</p>

## To-Do

<p align="justify">The range of calculated prime numbers should be variable in the future. It should also be possible to get prime numbers or composite numbers. It should also be possible to consecutive prime numbers. And the program should be able to print the number of counted prime numbers or composite numbers. The package needs also a function if a number is a prime number or a composite number.</p>

## Other Prime Number Programs

<p align="justify">I found so far two over Ubuntu installable programs with which prime numbers can be calculated [1,2].</p>
    
## References

[1]    manpages.ubuntu.com/manpages/noble/en/man1/primesieve.1.html

[2]    manpages.ubuntu.com/manpages/noble/man1/matho-primes.1.html

## See also

[GT]    github.com/guidotheelen/prime_numbers/blob/master/lib/prime_numbers.dart

[RM]    rimonmostafiz.github.io/blog/sieve-of-eratosthenes-memory-efficient-implementation/

[BG]    www&#8203;.baeldung.com/cs/prime-number-algorithms

<hr width="100%" size="1">

<p align="center">
It would be grateful if you decide to support the work here.
</p>

<hr width="100%" size="1">

<p align="center">If you like what I present here, and if it helps you above, donate me a cup of coffee :coffee:.<br>I drink a lot of coffee while programming and writing  :smiley:.</p>

<p align="center">
<a href="https://www.buymeacoffee.com/zentrocdot" target="_blank"><img src="\IMAGES\greeen-button.png" alt="Buy Me A Coffee" height="41" width="174"></a>
</p>

<p align="center">I loved the time when you could get also a hamburger :hamburger: for one euro!</p>

<hr width="100%" size="1">

<p align="justify">Here are some other good ways to simply donate a coffee to me via my favourite coins :moneybag:.</p>

<table>
  <tbody>
    <tr>
      <td>TQamF8Q3z63sVFWiXgn2pzpWyhkQJhRtW7</td>
      <td>Tron</td>
    </tr>
    <tr>
      <td>DMh7EXf7XbibFFsqaAetdQQ77Zb5TVCXiX</td>
      <td>Doge</td>
    </tr>
    <tr>
      <td>12JsKesep3yuDpmrcXCxXu7EQJkRaAvsc5</td>
      <td>Bitcoin</td>
    </tr>
    <tr>
      <td>0x31042e2F3AE241093e0387b41C6910B11d94f7ec</td>
      <td>Ethereum</td>
    </tr>
  </tbody>
</table>

<hr width="100%" size="1">

<p align="center">Page last modified 10/03/2024</p>



