# Brute-force-attack

The programme performs a brute force attack in five different phases. The objective is to find the actual passwords of 8 hashed passwords.

Phase 1
The programme reads the 10 most popular girl names in England a .txt file. It uses SHA-256 to hash the names and then compares the hashed password with the hashed values. An appropriate message, as well as the time elapsed to find the password are displayed in the screen. 
Names: http://homepages.cs.ncl.ac.uk/feng.hao/teaching/girl_names.txt

Phase 2
The programme reads the 10 most popular boy names in England a .txt file. It uses SHA-256 to hash the names and then compares the hashed password with the hashed values. An appropriate message, as well as the time elapsed to find the password are displayed in the screen. 
Names: http://homepages.cs.ncl.ac.uk/feng.hao/teaching/boy_names.txt

Phase 3
The programme reads the names from the aforementioned .txt files. It creates combinations with no specified case and with a number up to 9999 at the end (e.g. BoB17, aLICe1920). It uses SHA-256 to hash the output and then compares the hashed password with the hashed values. An appropriate message, as well as the time elapsed to find the password are displayed in the screen.

Phase 4
The programme reads a lower-case Engligh word from a .txt file consisting of every English word. It uses SHA-256 to hash the words and then compares the hashed password with the hashed values. An appropriate message, as well as the time elapsed to find the password are displayed in the screen.
File: http://homepages.cs.ncl.ac.uk/feng.hao/teaching/word_list_moby_all_moby_words.flat.txt

Phase 5
The programme creates words using 4 alphanumerical characters, with no specified case, and with special characters "_!@#$%^&*"(e.g. !tZP, Y@6a).It uses SHA-256 to hash the output and then compares the hashed password with the hashed values. An appropriate message, as well as the time elapsed to find the password are displayed in the screen.

