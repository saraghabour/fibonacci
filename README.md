fibonacci
=========

python code ,  actual number appear when enter any number "that will be index"

Using recursion ..

def fib(n):
  if n-1 == 1 : 
    Return 1
  if n-2 == 0 :
    Return 1
  Return fib(n-1) + fib (n-2)
  
  
Using Loop ..

def fib(n)
  a , b = 0 , 1
  for i in range (n) :
    a , b = b , a+b
  Return a  

