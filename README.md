password =("abc123")
count=0

while True:
  user=input("What's your username?")
  userpass=input("Enter your password? ")
  count=count + 1
  if password == userpass:
    print("Login accepted ," +" You tried " + str(count) + " times to login ")
  if count == 10 :
    print("You tried too many times, try again later")
  if password != userpass:
    print("Login denied, try again")
  else:
    break
