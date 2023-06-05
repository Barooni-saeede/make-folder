# make-folder


                                                       
***  make new folder in pythone ***            


Sometimes, it is necessary to create folders automatically.

1- First, you need to use OS library in Python. This library
   can be used by default, but it is better to call it once
   at the beginning of the program.

** If you need to create some folders:

2- create a list and put the names of the folders that we
   intend to create in order in the form of strings.

3- create a FOR and call:
   os.path.join(address,folder_name)
   the first array in parentheses specifies the location of the 
   folder and the second array specifies the name of the folder.

4- Using the IF and check that a folder with this name does not
   already exist:
   if not os.path.exists(folder_path):

5- create the new folder by:
   os.mkdir(folder_path)
