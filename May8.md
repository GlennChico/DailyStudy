# DailyStudy
Python3learning
# Modules:
## method</br>
 > import module_name  
 #### Use module_name.var
 > From module_name import var
 #### to only import var
 > From module_name import var as yourvarname
# Exception:
  1.application:to handle the exception,we use a “try/except” satement
  2.commontypes:ImportError,IndexError,NameError,SyntaxError,TypeError,ValueError
  #### example:
 >Try:
	>Num1=7
	>Num2=0
	>Print(num1/num2)
	>Print(“Done calculation”) //don’t work
>Except ZeroDivisionError:
	Print(“An error occurred due to zerodivision”)
Finally:
	Print(“finished the work”)
   4.Raising exceptions: //use it without arguments to raise exceptions;
   5.Assertions://function:place assertions at the start of a function to check for valid input and after a function call to check for valid output
# File:
   1. 4Modes: “r”,read mode ,default ;“w”,write mode,rewriting the text;”a”,append mode,adding new content to the end of the file;”b”,binary mode,used for non-text file
   2. Method:redline,to return a list in with each element is a line
   3. Statement:”with”//example,with open(“filename.txt”,”mode”) as f: “<—pay attention,there is a ‘:’ at the end of the sentence and file is automatically closed ”
# Data structure :
   1. List[]: list[num1:num2]//choose the elements from index1 to index2;list[num1:num2:num3]//num3:represent the step  
   2. Dict{}:
   3. Tuples(): //immutable,similar to list.feature :be faster but can not changed ,without the parenthess



