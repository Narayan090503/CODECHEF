# CODECHEF
MY CODECHEF PRACTICE
def gcd(x,y):
    if(y==0):
        return x
    else:
        return gcd(y,x%y)
    x=int(input())
    y=int(input())
    GCD=gcd(x,y)
    print(GCD)
