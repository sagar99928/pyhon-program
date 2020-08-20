# pyhon-program
import pyttsx3
import os

# pyttsx3.speak("Welcome to my tools")


while True:
	print("chat with me with your requirements : "  , end='')
	p = input()

	# print(p)
	# os.system(p)

	if (("run" in p) or ("open" in p) or  ("execute" in p ) or ("launch" in p)) and ("chrome" in p):
	  pyttsx3.speak("Welcome to chrome")
	  os.system("chrome")

	elif (("run" in p) or ("open" in p) or  ("execute" in p ) or ("launch" in p)) and  (("notepad" in p) or ("editor" in p)) :
	  pyttsx3.speak("Welcome to notepad")
	  os.system("notepad")

	elif (("run" in p) or ("open" in p) or  ("execute" in p ) or ("launch" in p)) and (("player" in p)  or ("media" in p)):
	  pyttsx3.speak("Welcome to wmplayer")
	  os.system("wmplayer")

	elif (("run" in p) or ("open" in p) or  ("execute" in p ) or ("launch" in p)) and (("player" in p)  or ("vlc" in p)):
	  pyttsx3.speak("Welcome to vlc player")
	  os.system("vlc")

	elif (("run" in p) or ("open" in p) or  ("execute" in p ) or ("launch" in p)) and ("firefox" in p):
	  pyttsx3.speak("Welcome to firefox")
	  os.system("firefox")
	
	elif  ("exit" in p)  or ("quit" in p):
	  break

	else:
	  print("dont support")


