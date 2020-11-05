
                                          HIGHER ORDER FUNCTIONS 

A function that takes a function as a parameter and returns a function.



Map function applies a defined function to all the iterables.

Filter function will return an iterator that contains all the elements 
        of the iterable for which the function called on it is Truthy.

ip function is not a higher order function. It's used to combine 2 or more arrays
     and it's based on the shortest(length) array.

List Comprehension is an alternative to Map function and it can simplify the code into a single
                    line expression. It can also act as an alternative to Filter


Partial Functions are used to reduce the total number of required arguments when calling a function.

Operator Module has many arithmetic functions like add, mul, pow, od, floordiv etc 
                 and boolean functions like lt, le, gt, ge etc. It's also called as convenience module.
                 

REDUCING FUNCTIONS recombine an iterable recursively ending up with a single return value.

                    Python has several built-in reducing functions like min, max, sum, any, all etc.


                                                         Assignment


1. To write a function using only list filter lambda that can tell whether a number is a Fibonacci number or not. A pre-calculated list/dict to store fab numbers till 10000 can be used.
   We use the following expression to check a number against a pre-calculated list of fibonacci numbers.

## From a pre-stored fibonacci list, a given number has to be checked if it's a fibonacci number

   "fib_check = lambda x : True if x in fib_list else False"



2. Using list comprehension (and zip/lambda/etc if required) write an expression that: 

From 2 lists, even number from 1st list and odd number from 2nd list should be added...using list comprehension, lambda/filter can also be used
(a) add 2 iterables a and b such that a is even and b is odd
    def even_odd(l1, l2): To add even numbers from l1 and odd numbers from l2.

Vowels should be stripped from a given string using list comprehension
(b) strips every vowel from a string provided (tsai>>t s)
    def strip_vowel_str(str): This function strips the vowels from an input string

RelU function should be defined using list comprehension
(c) acts like a ReLU function for a 1D array
    def relu_like_activation(l): when a list of positive and negative numbers is passed, this function treats all the negative numbers as zero.

sigmoid function should be defined using list comprehension
(d) acts like a sigmoid function for a 1D array
    def sigmoid_activation(l): returns a list of 1D array for a given list of numbers.

(e) takes a small character string and shifts all characters by 5 (handle boundary conditions) tsai>>yxfn
    


3. A list comprehension expression that takes a ~200 word paragraph, and checks whether it has any of the swear words mentioned
in https://github.com/RobertJGabriel/Google-profanity-words/blob/master/list.txt (Links to an external site.)

4. Using reduce function: 

(a) add only even numbers in a list
    def add_even_num(l): This function adds all the even numbers in a given list

Using reduce, lambda etc the biggest ascii character in a given string must be found
(b) find the biggest character in a string (printable ascii characters)
    def big_char_str(str): This function finds the biggest ascii character in a given string.

Using reduce, lambda function every third number must be added in a list
(c) adds every 3rd number in a list
    add_third_number: this expression adds every third number in a list.

Using randint, random.choice and list comprehensions, 15 random KADDAADDDD number plates must be generated, where KA is fixed, D stands for a digit, and A stands for Capital alphabets
5. Using randint, random.choice and list comprehensions, write an expression that generates 15 random KADDAADDDD number plates, 
   where KA is fixed, D stands for a digit, and A stands for Capital alphabets. 10<<DD<<99 & 1000<<DDDD<<9999
   num_plate: This expression returns a string of number plate where "KA" is fixed.


6. Write the above again from scratch where KA can be changed to DL, and 1000/9999 ranges can be provided. 
   Now use a partial function such that 1000/9999 are hardcoded, but KA can be provided


                                                                     
