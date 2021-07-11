# accept-a-file-name-from-the-user
filename = input("Input the Filename: ")

f_extns= filname.split(".")

print ("The extension of the file is : " + repr(f_extns[-1]))
