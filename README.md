x = (random.randint(1,101))
guess = int(input("Guess a number: "))
while True:
    if guess == x:
        print('Correct')
        break
    elif guess > x:
        print('Too high')
    else:
        print('Too low')
    guess = int(input("Guess a number: "))
