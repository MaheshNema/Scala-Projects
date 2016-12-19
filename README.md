# Scala-Projects

/* High order function 
*/

def HigherOFunc(f:Int=>Int,a:Int,b:Int):Int =
if (f(a)>a) 0 else 1

def PassingHigerOFunc(x:Int):Int = Square(x)

def Square(x:Int):Int = x*x

HigherOFunc(PassingHigerOFunc,1,2)
