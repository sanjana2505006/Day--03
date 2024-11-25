# Day--03
def sum_of_natural_numbers(n):     if n == 0:         return 0     else:         return n + sum_of_natural_numbers(n - 1) n=int(input()) result = sum_of_natural_numbers(n) print(result)
