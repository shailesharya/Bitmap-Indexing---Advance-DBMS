# Bitmap-Indexing---Advance-DBMS
Encode and Decode the given bits of 0's and 1's using Bitmap Index

Q = 100000001000 

Hint: 
Step 1: Count the no. of zeros (i) before 1 occurs 

Step 2: Print j-1 time '1' followed by a single '0'

Step 3: Print i in binary

i = 0  ('1' occurs 0 times)

j = 1  (j = No. of bits required to represent i -> log 2 (i))

o/p -> 00 (1st 0 because of step 2) (2nd zero for represent i in binary)

i = 7 (7 zeros before next 1 occure)

j = 3 (no. of bits require t represent 7 -> log (base 2) (7))

o/p -> 110111 (print j-1 times '1') (followed by 0) (followed by binary of 7)


Ans = 00110111

