# Bubble-Sort-1
Python Program for Bubble Sort


list = [ 7 , 4 , 10 , 9 , 3 , 5]

for j in range(len(list) - 1 , 0 , -1):

  for i in range(j):
  
    if list[i] > list[i+1]:
    
      temp = list[i]
      
      list[i] = list[i+1]
      
      list[i+1] = temp

print(list)
