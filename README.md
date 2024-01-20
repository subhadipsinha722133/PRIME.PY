# PRIME.PY
# prime number print

a=int(input('enter a nomver ='))
for i in range(2,a+1):
    for j in range(2, i):
        if (i%j)==0:
            break
    else:
       print(i)


