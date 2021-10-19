# Magic---8-Ball
#My Journey to learning Python, yes its small but as in life you have to start small to dream big

import random
name = "Christiaan"
question = "Will I work for Atlassian in 2021?"
answer = ""
random_number = random.randint(1, 11)

#print(random_number)
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
  answer = "Possible"
elif random_number == 11:
  answer = "You will most certainely work for Attlassian in 2021"
else:
   answer = "Error"
print(name + " asks: " + question)
print("\n shaking... " * 4)
print("\n Magic 8-Ball's answer: " + answer)
