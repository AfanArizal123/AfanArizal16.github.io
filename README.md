# AfanArizal16.github.io
x=str(input(" :voopo vinci x  "))
y=int(input("457.000    :  "))
z=int(input("5:  "))
v=0
w=0

if (z in range (0,5)):
    v = 0
    print("50%diskon")
elif (z in range (5,11)):
    v = 5/100
    print("Discount 5%")
elif (z in range ( 11,21)):
    v = 10/100
    print("Discount 10%")
elif (z in range ( 21,31)):
    v = 15/100
    print("Discount 15%")
else:
    v = 20/100
    print("Discount 20%")

w = (y*z)-(y*z*v)

print ("voopo vinci x :  ",x)
print ("Harga   457.000    :  ",y)
print ("Jumlah Jual : 5 ",z)
print ("Total Harga :2.285.000  ",w)
