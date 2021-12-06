# DSA
**Digital Signature Algorithm Implementation**

**Steps:**

1) Sync the code to local:

**git clone https://github.com/snehamaganahalli/DSA.git**

2) Install necessary libraries:

**sudo apt-get install libssl-dev**

**sudo apt-get install libgmp3-dev**

3) Compile the code

**gcc dsa.c  -lssl -lcrypto -lgmp**

4) Run

**./a.out**

=============================================

**Sample Output:**


Enter 1 to sign and 0 to verify:1

Signing!!!!!!!!!!!!!!!!!

Enter a message(number)  to sign

123

sign s1: 18

sign s2: 73

Enter 1 to sign and 0 to verify:0

Verifying!!!!!!!!!!!!!!!!!

Enter S1,S2

18,73  (Type same signature which sender has sent)

Enter the message(number) to be verified

123 (Type same message which sender has sent)

v: 18

 Verified successfully!!!!!!!!!!!!!!. The Receiver accepted the message

Enter 1 to sign and 0 to verify:0

Verifying!!!!!!!!!!!!!!!!!

Enter S1,S2

1,1 (Type some different signature than what sender has signed)

Enter the message(number) to be verified

1   (Type some diffrent message than what sender has sent)

v: 43

 Verification failed !!!!!!!!!!!!!!. The Receiver Rejected the message

Enter 1 to sign and 0 to verify:

==========================

**Name: Sneha Maganahalli Rajendranath**

**Roll No: CS21M522**
