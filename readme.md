Eliott Sobieraj



def multiplication(x: float, y: float) -> float:

	return x * y

def division(x: float, y: float) -> float:

	return x / y

def addition(x: float, y: float) -> float:

	return x + y

def subtraction(x: float, y: float) -> float:

	return x - y


from calculatric.py import *
if __name__ == "__main__":
print(f"6 + 3 = {addition(6,3)}")
print(f"6 * 3 = {multiplication(6,3)}")
print(f"6 - 3 = {subtraction(6,3)}")
print(f"6 / 3 = {division(6,3)}")