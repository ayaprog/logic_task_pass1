# logic_task_pass1
method which will remove any given character from a string 

string1 = input("Choose a string: ")
disallowed_characters = "._!"

for character in disallowed_characters:
	string1 =string1.replace(character, "")

print("Your string is: " + string1)
