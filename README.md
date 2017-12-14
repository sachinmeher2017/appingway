l1 = ['a','b','c']                    /*first input list
l2 = ['b','d']                        /*second input list
for i in range(0,len(l1)):            /*loop to check all elements
    if l1[i] not in l2:               /*check if the element of l1 is not present in l2 
        print(l1[i])                  /*print the element if above condition is satisfied
