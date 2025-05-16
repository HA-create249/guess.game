# guess.game

secret_word = "Alissar"
guess = ""
guess_count = 0
guess_limit = 3
out_of_guesses = False

print("Who is the girl that broke Hadi's heart?")

while guess != secret_word and not(out_of_guesses):
    if guess_count < guess_limit:
        guess = input("Enter guess: ")
        guess_count += 1
    else:
        out_of_guesses = True

if out_of_guesses:
    print("Out of guesses, YOU LOSE!")
else:
   print("That's right!")
   print("Hadi is a dumpass")
