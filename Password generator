import random
password_length = int(input('how long do you want your password to be? '))
def give_password(password_length):
	charcthers = '1234567890qwertyuiopasdfghjklzxcvbnm@#$&*()%-+=/!?€£¥_^§|~<>'
	password = []
	for i in range(password_length):
		char = str(random.choices(charcthers)).replace("['",'').replace("']",'')
		password.append(char)
	return str(password).replace("'",'').replace(", ","").replace("[","").replace("]","")
print(give_password(password_length))
