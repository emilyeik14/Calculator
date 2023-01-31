print("Let's do some math")
print('Enter 5 numbers')
nums = []
num1 = float(input())
nums.append(num1)
num2 = float(input())
nums.append(num2)
num3 = float(input())
nums.append(num3)
num4 = float(input())
nums.append(num4)
num5 = float(input())
nums.append(num5)
print("Let's calculate average")
avg = (num1+num2+num3+num4+num5)/5
print('The average is:',avg)
print("Let's calculate max")
largest_number = max(nums)
print('The max is:',largest_number)
print("Let's calculate min")
smallest_number = min(nums)
print('The min is:',smallest_number)
if smallest_number < 100:
    smallest_num = smallest_number * 100
    nums.append(smallest_num)
    smallest_number = min(nums)
    print('The new min is:',smallest_number)
else:
    largest_num = largest_number / 100
    nums.append(largest_num)
    largest_number = max(nums)
    print('The new max is:',largest_number)
![image](https://user-images.githubusercontent.com/75332573/215821766-e4650569-c4d8-4f59-b6db-f872f42ed0d7.png)

