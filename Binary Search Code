# binary search code:

def binary_search(values, to_find, start_index, end_index):
   if start_index > end_index:
      return False
   middle = (start_index + end_index) // 2
   if to_find == values[middle]:
      return True
   elif to_find < values[middle]:
      return binary_search(values, to_find, start_index, middle - 1)
   else:
      return binary_search(values, to_find, middle + 1, end_index)

values = [2,4,6,8,10,12,14,16,18,20]
n = int(input("Enter a number: "))
print(binary_search(values, n, 0, len(values) - 1))
