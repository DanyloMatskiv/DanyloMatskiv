
class Calculator:
 
    def add(self, a, b):
        return a + b
   
    def subtract(self, a, b):
        return a - b
   
    def multiply(self, a, b):
        return a * b
   
    def divide(self, a, b):
        if b != 0 and a != 0:
            return a / b
        else:
            return "No divide on 0!"
 
calc = Calculator()
print(calc.add(5,3))
print(calc.subtract(10,5))
print(calc.multiply(2,2))
print(calc.divide(0,2))
