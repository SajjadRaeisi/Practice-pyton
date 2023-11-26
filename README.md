def myfunc(n):
  return lambda a : a * n

mydoubler = myfunc(3)
mytripler = myfunc(6)

print(mydoubler(11)) 
print(mytripler(11))
