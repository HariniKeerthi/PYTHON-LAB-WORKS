[[[PRIME NUMBER OR NOT]]]

num=int(input("Enter a number:-"))
def prime (num):
  for i in range(2,num):
    if(num%i==0):
      print("It is not a prime number")
      break
    else:
      print("It is a prime number")
      break
prime(num)
----------------------------------------------------------------------
[[[COUNTING VOWELS AND CONSONENTS IN A WORD]]]

word=input("Enter the string")
def word_count (word):
  vowel=0
  consonant=0
  for j in word:
     if(j=='a' or j=='e' or j=='i' or j=='o' or j=='u' or j=='A' or j=='E' or j=='I' or j=='O' or j=='U'):
      vowel=vowel+1
  else:
    consonant=consonant+1
  print("Number of Vowels in word:-",vowel)
  print("Number of consonant:-",consonant)
word_count(word)
----------------------------------------------------------------------
[[[POSITIVE AND NEGATIVE NUMBERS]]]

list=[3,71,-1,56,36,-70,96,-19,47]
def numbers(num):
  pos=0
  neg=0
  for j in num:
    if(j>0):
      pos=pos+1
    else:
      neg=neg+1
  print("Number of positive numbers:",pos)
  print("Number of negative numbers:",neg)
numbers(list)
----------------------------------------------------------------------
[[[RANGING FROM 1 TO 25 BUT EXCLUDING NUMBERS WHICH IS MULTIPLE AS 5]]]

def num(range):
  a=1
  b=25
  for i in range(a,b+1):
    if(i%5!=0):
      print(i)
num(range)
----------------------------------------------------------------------
[[[PRODUCT OF TWO NUMBERS IF THE PRODUCT IS GREATER THAN 500,THEN RETURN THEIR SUM]]]

def product_or_sum(n1,n2):
  sum=0
  rem=0
  product=n1*n2
  if(product > 500):
    print("product of ",n1," and ",n2," is greater than 500 ")
    print("Their product is : ",product)
    while(product>0):
      rem = product % 10
      sum=sum+rem
      product=product//10
    print("So, sum of their product is: ",sum)
  else:
    print("product is : ",product)

num1=int(input("enter number1: "))
num2=int(input("enter number2: "))
product_or_sum(num1,num2)
-----------------------------------------------------------------------------
