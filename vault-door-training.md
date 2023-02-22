# Title: vault-door-training
### Category: Reverse Enginnering
### Event: picoCTF2019
### Points: 50

### Description:
Your mission is to enter Dr. Evil's laboratory and retrieve the blueprints for his Doomsday Project. The laboratory is protected by a series of locked vault doors. Each door is controlled by a computer and requires a password to open. Unfortunately, our undercover agents have not been able to obtain the secret passwords for the vault doors, but one of our junior agents obtained the source code for each vault's computer! You will need to read the source code for each level to figure out what the password is for that vault door. As a warmup, we have created a replica vault in our training facility. The source code for the training vault is here: VaultDoorTraining.java

### let's put on our cap!
It seems like a normal Java file, let's check it out. Hhmmm.... seems like code it self prompt user to enter password and compare password with set key.  Could it be... the flag itself?

"Don't compile and run the program if you don't understand what it do."