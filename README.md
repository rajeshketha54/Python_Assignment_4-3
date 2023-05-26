# Python_Assignment_4-3
def square(n):                     #Sample List: [4, 5, 2, 9]
    return n**2
lst=eval(input())                  #Expected Output: [16, 25, 4, 81]
result=list(map(square,lst))
print(result)                      #My output: [16, 25, 4, 81]
