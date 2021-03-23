# pycthon
A solution to call C in python and pass arguments via socket or file or something that works not like Cython!
## The story
As I walk through the valley of the shadow of death, I noticed something extra wierd about python!! It is a EXTRA SUPER SLOW!!!!!  
As the days passed by I strived to find a language that is fast enough for me to make a O(n^2) program for n greater than 100 000 to finish in a time near to the same program in C, but I failed so hard, you can read the journey in O(n^2) journey section.  
Next I decided to use C in the python code directly so I started another journey and again confronted some problems that make it slow again even with extending python with c or using cython, there is a little chance that I was doing wrong and will investigate it later, you can read about it in no sir you cant be fast section.
At last I came up with a strange idea what if we look at the problem as the python section needs a hard work to be done with a C service program that gets called within but passes argumants and data with another way to make it work independently from main program?? forget cython garbage just write a program in C and it reads data from files or from unix sockets or another solution, totally C no way that will be slow at all, and I decided to solve the O(n^2) problem with this solution.

## python or pyslow?
Here is prove that python is slomoest programming language... complete later

## the O(n^2) journey  
Testing the same program in different languages resulted in some interesting events.
### first try golang  
I was very interested and ... complete later

## no sir you cant be fast
Seems like if you pass argumants directly it will still be python code.
### cython
Takes exactly the same time if you pass argumants directly.

## solution architecture
hmmm... complete later
