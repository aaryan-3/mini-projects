import random
def roll_dice():
    return random.randint(1,6)
def main():
    print("Welcome to Dice Simulator")
    while True:
        user_input= input("Press R to roll the dice or Q to quit.").lower()
        if user_input=="r":
            result=roll_dice()
            print(f'You rolled a {result}!')
        elif user_input=="q":
            print("Thanks for playing, Goodbye!")
            break
        else:
            print("Invalid input, please try again.")
if __name__ == "__main__":
    main() 
