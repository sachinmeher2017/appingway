l1 = ['a','b','c']             /*list 1 as input 
l2 = ['b','d']                 /*list 2 as input
for i in range(0,len(l1)):     /*loop to check the values
    if l1[i] not in l2:        /*if clause to check elements whuch are in l1 but not in l2        
        print(l1[i])           /*if above condition satisfies it print the corresponding element
