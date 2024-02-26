# multiplication
num_1 = 2
num_2 = 3
product = num_1 * num_2
print("Product of {} and {} is {}".format(num_1, num_2,product))
# approach-2
def multiply_numbers():
    num_1 = float(input("Enter the first number: "))
    num_2 = float(input("Enter the second number: "))

    product = num_1 * num_2

    print(f"Product of {num_1} and {num_2} is {product}")
# approach-3
my_list = [1, 2, 3]
result = my_list * 3
print(result)  
# approach-4
import numpy as np

array1 = np.array([1, 2, 3])
array2 = np.array([4, 5, 6])
result = np.multiply(array1, array2)
print(result)  
