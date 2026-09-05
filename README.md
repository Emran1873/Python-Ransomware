# Python-Ransomware

To test the Ransomware out on your machine,

* edit lines 49 and 140 in the ransomware.py file with your own absolute paths etc for testing purposes and so you can use the localRoot folder

* [ATTACKER] Run the RSA script to generate two keys, a private and public key

* [TARGET] Run the ransomware script - localRoot .txt files will be encrypted now

* [ATTACKER] Run the fernet key decryption file to decrypt the EMAIL_ME.txt(be on your desktop) file, this will give you a PUT_ME_ON_DESKtOP.txt file, once you put this on the desktop the ransomware will decrypt the localRoot files in that directory
