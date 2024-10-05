son = int(input("Son kiriting : "))
b = 0
c = 0

while son != 0 :
    a = son % 10
    son = son // 10
    if a % 2 == 0 :
        b = b + 1
    c = c + 1
if b == c :
    print("True")
else :
    print("Falce")
