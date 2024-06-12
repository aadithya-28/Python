kbRows = "qwertyuiop", "asdfghjkl", "zxcvbnm"
inList, outList = [input() for _ in range(int(input()))],[]

for word in inList:
    for row in kbRows:
        if set(word.lower()).issubset(set(row)):
            outList.append(word)
            
if outList : print(*outList, sep='\n'); exit();
print('No words')
