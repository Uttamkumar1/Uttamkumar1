fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = []
i=0
for x in fruits:
     if fruits[i][0]=='a':
            newlist.append(x)
            i=i+1
            print(newlist)
