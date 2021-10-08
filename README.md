# Assigment-1

func EvenOdd(number: Int){
  if(number < 0){
    print("Number is negative.")
}
  else if(number % 2==0){
    print("Number is even.")
  }
  else{
    print("Number is odd.")
  } 
}

print("Enter number=")
var no=Int(readLine() ?? "0") ?? 0
EvenOdd(number:no)

