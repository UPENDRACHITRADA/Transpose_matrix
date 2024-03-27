X = [[0,0],
    [0 ,0],
    [0 ,0]]
for i in range(0,3):
  for j in range(0,2):
    value=int(input("Enter X matrix :"))
    X[i][j]=value print("\nX Matrix is")
for r in X: print(r)
result = [[0,0,0],
           [0,0,0]]
for i in range(len(X)):
  for j in range(len(X[0])):
result[j][i] = X[i][j]
print("\nTranspose Matrix is ")
for r in result:
  print(r)
