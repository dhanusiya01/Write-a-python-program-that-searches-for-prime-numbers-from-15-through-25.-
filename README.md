# Write-a-python-program-that-searches-for-prime-numbers-from-15-through-25.-
for a in range(15,25):
    k=0
    for i in range(2,a//2+1):
        if(a%i==0):
            k=k+1
        if(k==0):
            print(a)

OUTPUT:

15
17
17
17
17
17
17
17
19
19
19
19
19
19
19
19
21
23
23
23
23
23
23
23
23
23
23


