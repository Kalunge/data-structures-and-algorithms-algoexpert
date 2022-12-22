## Complexrity analysis
- The process of determining how efficieant an algorithm is. Complexity analysis involves finding both the time and space complexity of an algorithm. 
- Complexity analysis is effectively used to determine how 'good' an algorithm is and whether it is better than another oe.  
### Time complexity
- how fast an algorithm runs -> the faster the better
- A measure of how fast an algorithm runs, time complexity is a central concept in the field of algorithms and in coding interviews. 
- It is expressed in form of Big O Notation
- [
  0  | 1  | 2  | 3
  4  | 5  | 6  | 7
  8  | 9  | 10 | 11
  12 | 13 | 14 | 15
  16 | 17 | 18  | 19
]

### 
a = [1,2,3 ...]
- change of speed of an algorithm with change in input size
##### O(1) 
  - Remains constant with increase in input
- f(a) => 1 + a[o]
##### O(N) 
  - Increases linearly with increase in input size
- f(a) => sum(a)
##### O(N2) 
- f(a) => pair(a)
  - 


### Space complexity
- what space/memory takes -> The less the better
- A measure of how much auxiliary memory an algorithm takes up, space complexity is a central concept in the field of algorithms and coding interviews
- It is expressed using Big O Notation

### Space-Time complexity

- Aim to choose the best DS with the best space and time complexity

## Memory
### Bit
- short for bunary digit, a bit is a fundamental unit of information in Computer Science that represents a state with one of two values, typically 0 and 1
- Any data stored in a computer is, at the most basic level, represented in bits
### Byte
- Agroup of 8 bits for example 01101000 is a byte
- A single byte can represent up to 256 data values(2)8
- Since a binary number is a number expressed with only two symbols, like 0 and 1, a byte can effectively represent all of the numbers between 0 and 255, inclusive, in a binary format
- the following bytes represent the numbers 1,2,3 and 4 in binary format
```
1: 00000001
2: 00000010
3: 00000011
4: 00000100
```
### Fixed Width Integer
- An integer represented by a fixed amount of bits. for example, a 32-bit integer is an integer represented by 32 buts (4 bytes) and a 64-bits integer ia an integer represented by 64 bits(8 bytes)
- the following is the 32-bit representation of the number 1, which clearly separates the bytes
``` 
0000000 000000 000000 000001 
```
- The following is a 64 bit representation of the number 10 with clearly separated bytes
```
0000000 000000 0000000 0000000 0000000 0000000 00000000 000001010
```

-Regardles of how an integer is, its fixed-width-integer representaion, is by definition, made up of a constant number of bits.
-It follows that, regardless of how large an integer is, an operation performed on its fixed-width-integer represantation consists of a constant number of bit manpulations, since the integer is made up of a fixed number of bits. 

### Memory
Broadly speaking, memory is the foundational layer of computing, where all data is stored
in the context of coing interviews, it is important to ot the following points.
- Data stored in memory is store in bytes and, by extension, bits
- Bytes in memory can 'point' to other bytes in memory, so as to store refences to other data.
- The amount of memory that a machine has is bounded , making it valuable to limit how much memory an algorithm takes up.
- Accessing a byte or a fixed number of bytes (like 4 or 8 bytes in the case of 32 abd 64 bit integer) is an elementary operation, which can be loosely treated as a single unit of operational work. 

### Big O Notation
The notation used to describe the time and space complexity of algorithms.

Variables used in Big O Notation denote the sizes of inputs to algorithms. For example O(N) might be the time complexity of an algorithm that traverses through an array of length N; similaryly O(n + m) might be the time complexity of an algorithm that traverses through an array of length n and through a string of length m

- Constant : O(1)
- Logarithmic: O(log(n))
- Linear: O(n)
- Log-Linear: O(nlog(n))
- Quadric: O(n squared)
- Cubic: O(n power 3)
- Exponential: O(2 power n)
- Factorial: O(n!)

Note that in the context of coding interviews, Big O Notation is usually understoodnto describe the worst case complexity of an algorithm, even though the worst case complexity might differ from the average-case complexity

For example, some sorting algorithms have different time complexities depending on the layout of elements in the input array. In rare cases, their time complexitt will be much worse than in more common cases. Similarly an algorithm that thakes in a string and performs special operations on upper case caracters might have a different time complexity when run on an input string of only upper case characters vs on an input string with just a few upper case characters.

Thus when describing the time complexty of an algorithm, it can be sometimes helpful to specify whether the time complexity refers to the average case or the worst case eg 'this algorithm uns in O(n log(n)) time on average and in O(n squared) time in the worst case'.

### Logarithm



