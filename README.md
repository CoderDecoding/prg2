#program2 (pattern printing)(DIAMOND - ASTRISK)

n = 5                                      
def print_star_pattern(n):
   for i in range(1 ,n):
     print(" " *(n-i), end="") 
     for j in range(i):
        print("*",end=" ")
     print()
   for i in range(n , 0 , -1):
         print(" " *(n-i), end="")
         for j in range(i):
            print("*",end=" ")          
         print()
print_star_pattern(n)
