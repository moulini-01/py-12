# py-12
printing diamond shape using numbers 
n=5
for i in range(n):
    for j in range(n-i-1):
	 	  print("  ", end="")
    for k in range(i+1):
  	 	  print(i+1,end=" ")
    for l in range(i):
  	      print(i+1,end=" ")
    print( " ")
k=5
for m in range(k):
    for n in range(m+1):
	 	  print("  ", end="")
    for o in range(k-m-1):
  	 	  print(k-m-1,end=" ")
    for p in range(k-m-2):
  	      print(k-m-1,end=" ")
    print(" ")
