# Counting-game
print("you are to count numbers from 1 to 21")
choice = int(input("if you want to start counting press 1 else 0: "))
if(choice ==1):
    count =0
    while(count<=21):
        count = int(input("you: "))
        if(count == 21):
            print("YOU LOSE!")
        else:
            print("comp: ",count+1)
if(choice ==0):
    count = 0
    while(count<=21):
        print("comp: ",count+1)
        if(count == 20):
            print("COMP LOSES!")
        else:
            count = int(input("you: "))
            
