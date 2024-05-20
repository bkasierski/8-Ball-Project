# 8-Ball-Project
Ask the Magic 8-Ball anything and see what you get!

import random
random_number = random.randint(1,12)
# print(random_number)

name = "Ben"

question = "Will I pass my ENG 491 class?"

answer = ""

if random_number == 1:
  answer = "Yes - definitely"
elif random_number == 2:
  answer = "It is decidedly so"
elif random_number == 3:
  answer = "Without a doubt"
elif random_number == 4:
  answer = "Reply hazy, try again"
elif random_number == 5:
  answer = "Ask again later"
elif random_number == 6:
  answer = "Better not tell you now"
elif random_number == 7:
  answer = "My sources say no"
elif random_number == 8:
  answer = "Outlook not so good"
elif random_number == 9:
  answer = "Very doubtful"
elif random_number == 10:
  answer = "Possibly"
elif random_number == 11:
  answer = "Never"
elif random_number == 12:
  answer = "How could you ask such a question?"
else:
  answer = "Error"

if question == "":
  print("Please ask Magic 8-Ball a question to receive your fortune.")
else:
  print(name, "asks:", question)
  print("Magic 8-Ball's answer:", answer)




