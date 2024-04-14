#UNFINISHED!!

pwd = input("What is the master password? ")


def view():
    with open("passwords.txt", "r" ) as f:
        for line in r.readlines():
            data = line.rstrip()
            user, passw = data.split("|")
            print("User:", user, "| Password:", passw)

def add():
    name = input("Account Name: ")
    pwd = input("Password: ")
    
    with open("passwords.txt", "a" ) as f:
        f.write(name + "|" + pwd + "\n")
        #w means write overrides files and clears them
        #r means just read the file will run into problem if file doesn'st exist
        #a means it adds something to the end of the existing file it will create a new file if the selected one does not exist
        #\n creates a new line 



while True:
    mode = input("Would you like to add a new password or view existing ones(view/add/q)?  ")
    if mode == "q":
        quit()

    if mode == "view":
        view()
    elif mode == "add":
        add()
    else: 
        print("Invalid mode. ")
        continue
