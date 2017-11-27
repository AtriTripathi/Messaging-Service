# Messaging-Service

This is a Menu driven program in low-level C language, which accomplishes Messaging service with data encryption. The program makes use of AES Encryption & Decryption Algorithm.

The following modifications were made to the algorithm:-
+ Made use of only 1 key, to improve Encryption & Decryption time for smaller messages.
+ It involves total 9 round of Byte Substitution, Shift Row, Mix Column and Add Key.
+ The 10th round excludes the Mix Column.
+ A 128-bit Random Key was used for Encryption and Decryption purpose.

Future Prospects: Add Socket Programming
