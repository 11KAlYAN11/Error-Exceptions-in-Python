# Error-Exceptions-in-Python

n1 = int(input("Enter a number: "))
n2 = int(input("Enter a another number: "))
try:
    print(n1/n2)
except ZeroDivisionError:
    print("Zero division not possible")
except TypeError:
    print("Enter a valid input")
except ValueError:
    print("Enter a valid valued input")
except:
    print("Invalud input")
else:
    print("No Errors is occued")
finally:
    print("Process successfully completed")
    
"""
n1 = int(input("Enter a number: "))
try:
    if n1<=0 and n1 >12:
        print("Invalid month")
except:
    print(":")
"""
