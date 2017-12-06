# Messaging-Service

This is a menu driven program developed in low-level C language, which accomplishes Messaging service with encryption of user data. It makes use of highly secure **AES Encryption & Decryption Algorithm**.

## How it Works?

The program incorporates a menu prompt, with regular refreshing and clearing of screen with updated data on the CLI.
To begin with, it prompts the user to first _Register_ an account or _Login_, with their credentials like Name, Gender, Username, Password (Note: A new user has to Register himself first). After they Login, they are brought to their _Dashboard_, from where they can perform operations like Sending, Viewing, Deleting a message to some other registered user, together with an option to Exit the program. In addition, each screen also gives a prompt to either continue or go back depending upon the menu control, the user wants.

## The following modifications were made to the algorithm:-
+ It uses only 1 key, to improve Encryption & Decryption time for smaller messages.
+ It involves total 9 round of Byte Substitution, Shift Row, Mix Column and Add Key.
+ The 10th round excludes the Mix Column, while retaining the other 3 operations.
+ A 128-bit Random Key is used for Encryption and Decryption purpose.

## Future Prospects: 

Use Socket Programming concepts.

##### Don't forget to Star this Repo, make sure to Fork it, tinker with it, raise your Pull Request and finally come up with better versions of this program. :)
