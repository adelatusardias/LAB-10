# LAB-10
Dictionary
def ganjilTerbanyak(array) :
    angka = dict()
    for x in array :
        if x % 2 != 0 :
            a = array.count(x)
            if a % 2 != 0 :
                angka [x] = a               
    print(max(angka, key= angka.get),"muncul sebanyak",angka.get(max(angka,key= angka.get)))

test = [1,4,2,1,7,0,7,9,3,10,6,5,2,4,9,10,4,2,0,7]
ganjilTerbanyak(test)
