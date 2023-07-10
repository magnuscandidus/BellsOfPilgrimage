# BellsOfPilgrimage
T = int(input())
for W in range(T):
    N, X, K, P = map(int, input().split())
    if K>X:
        A = P+((10*(X))+(5*(K-X)))
    else:
        A = P+(10*K)
    if K==N:
        A=A+20
    print(A)
