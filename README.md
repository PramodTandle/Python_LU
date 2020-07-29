# Python_LU
#Assignment
(1)
#key to value and value to key

val1= {21:"FTP", 22:"SSH",23:"talent",80:"http"}
val2={value : key for key,value in val1.items()}
print(val2)

(2)
#sum of tuple in the list

list1=[(1,2),(3,4),(5,6),(4,5)]
res=[]
for i in range(0,len(list1)):
    a,b=list1[i]
    res.append(a+b)
print(res)


(3)
#making as one list

list1=[(1,2,3),[1,2],['a','hit','less']]
list2=[]
list2=[i for j in list1 for i in j]
print(list2)
