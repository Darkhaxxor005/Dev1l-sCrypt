# Dev1l-sCrypt

This tool is created to encrypt your python codes into random algorithm comes with both version of python 2,3 in linux.
If you want to encrypt a python file which runs python3 then you have to run this tools python3 form  or  if you are willing
for python2 then same goes to 2. 


 * Useage :

- sudo  python Dev1lcrypt.py --file=backdoor.py --output=output_backdoor.py # Python2 Code Encryption
- sudo  python3 Dev1lcrypt3.py --file=backdoor.py --output=output_backdoor.py # Python3 Code Encryption

 - sudo python Dev1lcrypt.py --help  or  sudo python3 Dev1lcrypt3.py --help #Show this messeage 
 - sudo python Dev1lcrypt.py --backdoor-file=payload.py --file=test.py --output=hacked.py  or  sudo python3 Dev1lcrypt3.py --backdoor-file=payload.py --file=test.py --output=hacked.py    #inject payload.py with  test.py into hacked.py with multi-threading system
 
 # How it work ? 
 
 * Encryption module :
 
 - Dev1l'sCrypt add some junkcode .
 - Dev1l'sCrypt use a python internal module 'py_compile' who compile the code into bytecode to a .pyc file .
 - Dev1l'sCrypt convert .pyc file into normal .py file .
 - And in this way we can obfuscate the code
 - The md5sum will change too
 
* Injection  module :

- it inject a malicious python file  into a normal file with multi-threading system .




 
 


 
