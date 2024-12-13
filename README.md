# AdadChap.py
https://quera.org/problemset/9774
n = input()


for x in n :
    chap = ""
    for i in range(0 , int(x)) :
        chap = chap + str(x)

    
    print("{0}: {1}".format(x,chap))
