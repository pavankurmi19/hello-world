def evenodd(n):
  if(n==0):
    return true
  elif(n==1):
    return false
  else:
    evenodd(n-2)
  
