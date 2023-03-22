def ANDgate():
    print("____AND GATE____")
    print("-----------------------------")
    for i in range(0,4):
        a=int(input("Enter A: "))
        b=int(input("Enter B: "))
        if(a==1 and b==1):
            print(i+1,"Output is:",1)
        else:
            print(i+1,"Output is:",0)
    print("-----------------------------")
def ORgate():
    print("____OR GATE____")
    print("-----------------------------")
    for i in range(0,4):
        a=int(input("Enter A: "))
        b=int(input("Enter B: "))
        if(a==0 and b==0):
            print(i+1,"Output is:",0)
        else:
            print(i+1,"Output is:",1)
    print("-----------------------------")
def NOTgate():
    print("____NOT GATE____")
    print("-----------------------------")
    for i in range(0,2):
        a=int(input("Enter A: "))
        if(a==0):
            print(i+1,"Output is:",1)
        else:
            print(i+1,"Output is:",0)
    print("-----------------------------")
def NANDgate():
    print("____NAND GATE____")
    print("-----------------------------")
    for i in range(0,4):
        a=int(input("Enter A: "))
        b=int(input("Enter B: "))
        if(a==1 and b==1):
            print(i+1,"Output is:",0)
        else:
            print(i+1,"Output is:",1)
    print("-----------------------------")
def NORgate():
    print("____NOR GATE____")
    print("-----------------------------")
    for i in range(0,4):
        a=int(input("Enter A: "))
        b=int(input("Enter B: "))
        if(a==0 and b==0):
            print(i+1,"Output is:",1)
        else:
            print(i+1,"Output is:",0)
    print("-----------------------------")
def XORgate():
    print("____XOR GATE____")
    print("-----------------------------")
    for i in range(0,4):
        a=int(input("Enter A: "))
        b=int(input("Enter B: "))
        if( a==b ):
            print(i+1,"Output is:",0)
        else:
            print(i+1,"Output is:",1)
    print("-----------------------------")
def XNORgate():
    print("____XNOR GATE____")
    print("-----------------------------")
    for i in range(0,4):
        a=int(input("Enter A: "))
        b=int(input("Enter B: "))
        if( a==b ):
            print(i+1,"Output is:",1)
        else:
            print(i+1,"Output is:",0)
    print("-----------------------------")


ANDgate()
#ORgate()
#NOTgate()
#NANDgate()
#NORgate
#XORgate()
#XNORgate()


