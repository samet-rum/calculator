#HESAP MAKINESI
def toplama(a,b):
    return a + b

def cikarma(a,b):
    return a - b

def carpma(a,b):
    return a * b

def bolme(a,b):
    return a / b

#-----------------------------------------------
a = None
b = None
islem = None
#-----------------------------------------------

while (True):
    a = input('bir deger giriniz: ')
    b = input('bir deger giriniz: ')
    islem = input('yapmak istediginiz islemi giriniz: ')
    try:
        a = int(a)
        b = int(b)
    except ValueError:
        print('invalid number error')
        islem = None

    if (islem != None):
        if islem == '+':
            print("Toplam: ", toplama(a,b))
        elif islem == '-':
            print("Cikarim: ", cikarma(a,b))
        elif islem == '*':
            print("Carpim: ", carpma(a,b))
        elif islem == '/':
            print("bolum: ", bolme(a,b))
        else:
            print("invalid operation...")
        q = input('Quit? [y/n]')
        if (q == "y" or q == "Y"):
            break
#------------------------------------------------
