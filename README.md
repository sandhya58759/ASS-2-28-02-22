# ASS-2-28-02-22
PROGRAM TO PRINT NOT REPEATING ELEMENTS IN LIST
x=[1,2,1,3,2,4,2,5,4,6,5,7,6,4]
list=[]
for i in  x:
    if i not in list:
        if x.count(i)==1:
            print(i)
        OUTPUT:
        [3 7]
        
        


        
        
        
