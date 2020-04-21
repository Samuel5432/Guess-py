import random
print("Choose a level:\n1.Easy\n2.Medium\n3.Hard")
ch=int(input("Press number:"))


if(ch==1):
    guesses=6
    random_number=random.randint(1,10)
    print(random_number)
    while guesses>0:
        user_number=int(input("\nGuess the number:"))
        if random_number==user_number:
            print("Right guess!!")
            break
        else:
            guesses=guesses-1
            print("\nThat was wrong!!\nChance(s) Left:",guesses)

elif ch==2:
    guesses=4
    random_number=random.randint(1,20)
    while guesses>0:
        user_number=int(input("\nGuess the number:"))
        if random_number==user_number:
            print("Right guess!!")
            break
        else:
            guesses=guesses-1
            print("\nThat was wrong!!\nChance(s) Left:",guesses)

elif ch==3:
    guesses=3
    random_number=random.randint(1,50)
    while guesses>0:
        user_number=int(input("\nGuess the number:"))
        if random_number==user_number:
            print("Right guess!!")
            break
        else:
            guesses=guesses-1
            print("\nThat was wrong!!\nChance(s) Left:",guesses)

if guesses==0:
    print("Game Over!!")


        
