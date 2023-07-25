# Simple_Calculator
#A simple calculator using Python Operators and loop 
while True:
    a=int(input('Enter your first number:'))
    d=int(input('Enter your Second number:'))
    f='1.add'
    s='2.sub'
    t='3.Multiply'
    fo='4.Divide'
    print(f,end=' '),print(s,end=' '),print(t,end=' '),print(fo)
    choice=input('Choose one operation:')
    if choice=='1':
        print("Answer:",a+d)
    elif choice=='2':
        print('Answer:',a-d)
    elif choice=='3':
        print('Answer:',a*d)
    elif choice=='4':
        print('Answer:',a/d)
    else:
        print('Invalid')
    exit=input('Do you want to exit,Yes/No:')
    print(exit)
    if exit.lower()=='yes':
        break
    else:
        continue
