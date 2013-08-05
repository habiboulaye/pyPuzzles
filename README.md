pyPuzzles
=========

Have fun with puzzles (coming soon)


1/ InplaceSwap

  Write a function that permutes 2 numeric values without using any additional temp variable 
    
  Example:
  
      > A=10, B=42
      > InplaceSwap(A,B)
      > print("A={0},B={1}".format(A,B))
      > A=42, B=10
      
  Trick: +/-
  
2/ stringSum

  Write a Function that takes two strings as input (x and y) representing two integer values and returns a
  string representing the sum of x and y. 
  
  For instance, 
  
      - given the inputs x = “12345678901234567890” and y = “23232323232323232324”
      - the function must return “35578002133557800214”. 
      
  The function must be able to operate on and compute the result of string inputs of arbitrary length!
    
  Trick: no
  
3/ MicroIndex
  Write a Console Application that loads a text file, takes a pair of words as input (x and y), and returns the number of
  times the two words appear adjacent (x after y or y after x) in the text file and the list of positions at which they appear.
  For instance, given the input text file contains “a b c d b a”, for the input pair <”a”, “b”> it will return 2 as the number of
  times the two words appear adjacent in the text and <0, 8> as the list of positions at which the pairs appear.
  It can be safely assumed that the input file is small enough to fit in memory of the machine hosting the application.
