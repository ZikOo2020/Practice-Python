#List_Remove_Duplicates
#Exercise_14

def insert_list():
    list_org = []
    flag = True
    while flag:
        insert = input("Please Insert The Value you Want: ,  don't forget you can done when you insert  Q:  ")
        insert_str = str(insert)
        if insert_str == "Q" or insert_str =="q":
            flag= False
        else:
            insert = int(insert)
            list_org.append(insert)
    print(list_org)
    check_list(list_org)


def check_list(a): 
    list_new= a
    number = set(list_new)
    number = list(number)
    print(number)
    
    
insert_list()  
