# reverseOrdderStrng

# 1st WAY -------------------------------->

s="Learnig python is very easy"
l=s.split()
print(l)
l1=l[::-1]
print(l1)
output=(''.join(l1))
print=(output)

# 2nd WAY -------------------------------->

s=input("Enter some string")
l=s.split()
l1=[]
i=len(l)-1
while i>=0:
    l1.append(l[i])
    i=i-1
    output=''.join(l1)
    print(output)
