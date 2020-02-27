# python-programming
def p1():                                   #for n=5
    n=int(input("enter value of n"))        #*
    for i in range(1,n+1):                  #* *
        print()                             #* * *
        for j in range(1,i+1):              #* * * *
            print("*",end=" ")              #* * * * *


def p2():                                   #for n=5
    n=int(input("enter value of n"))        #* * * * *
    for i in range(1,n+1):                  #* * * *
        print()                             #* * *
        for j in range(n,i-1,-1):           #* *
            print("*",end=" ")              #*



def p3():                                   #FOR N=5
    n=int(input("enter value of n"))        #*
    for i in range(1,n+1):                  #* *
        print()                             #* * *
        for j in range(1,i+1):              #* * * *
            print("*",end=" ")              #* * * * *
    for i in range(1,n):                    #* * * *
        print()                             #* * *
        for j in range(n,i,-1):             #* *
            print("*",end=" ")              #*
        


def p4():                                   #for n=5
    n=int(input("enter value of n"))    
                                            #1 2 3 4 5
    for i in range(1,n+1):                  #2 3 4 5
        print()                             #3 4 5
        for j in range(n,i-1,-1):           #4 5
            print(i,end=" ")                #5
            i=i+1                           



def p5():                                   #FOR N=4
    n=int(input("enter value of n"))        
    for i in range(1,n+1):                  #A 
        print()                             #A B 
        for j in range(65,65+i):            #A B C
            print(chr(j),end="  ")          #A B C D



def p6():
    n=int(input("enter value of n"))        #for n=5
    a=chr(65)                               
    for i in range(1,n+1):                  #A A A A A
        print()                             #B B B B
        for j in range(n,i-1,-1):           #C C C
            print(a,end=" ")                #D D




def p7():                                   #for n=5
    n=int(input("enter value of n"))        #1
    for  i in range(1,n+1):                 #1 2
        print()                             #1 2 3
        for j in range(1,i+1):              #1 2 3 4 
            print(j,end=" ")                #1 2 3 4 5 
            

def p8():
    n=int(input("enter value of n"))        #for n=5
    c=1
    for i in range(1,n+1):                  #1
        print()                             #22
        for j in range(1,i+1):              #333
            print(c,end="")                 #4444
        c=c+1                               #55555



def p9():
    n=int(input("enter value of n"))        #for n=4
    c=0
    for i in range(1,n+1):                  #0
        print()                             #12
        for j in range(1,i+1):              #345
            print(c,end='')                 #6789
            c=c+1                           



def p10():
    n=int(input("enter value of n"))        #for n=5
    c=1
    for i in range(1,n+1):                  #    1
        print()                             #   12 
        for j in range(n,i,-1):             #  123 
            print(" ",end="")               # 1234
        for k in range(n,n-i,-1):           #12345
            print(c,end='')                 
            c=c+1                           
        c=1



def p11():
    n=int(input("enter value of n"))      #for n=5
    for i in range(1,n+1):
                                          
        for j in range(n,i,-1):           
            print("  ",end='')            #        1
        for k in range(1,i+1):            #      1 2 1
            print(k,end=' ')              #    1 2 3 2 1
        for l in range(i-1,0,-1):         #  1 2 3 4 3 2 1
            print(l,end=' ')              #1 2 3 4 5 4 3 2 1
        print()   
            


def p12():
    n=int(input("enter value of n"))        #for n=5
    for i in range(1,n+1):
        print()                             #    1
        for  j in range(n,i,-1):            #   2 2
            print(" ",end='')               #  3 3 3
        for k in range(1,i+1):              # 4 4 4 4
            print(i,end=' ')                #5 5 5 5 5
                            
