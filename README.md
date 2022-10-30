# Burp Suite Professional Installation steps for Windows

--> Open Powershell and execute below command to set Script Execution Policy.
	Set-ExecutionPolicy -ExecutionPolicy bypass -Scope process
--> Now Execute Windows_Setup.ps1 file in Powershell to Complete Installation.
	./Windows_Setup.ps1
--> For Start Menu Entry, copy **Burp-Suite-Pro.vbs** file to 
	C:\ProgramData\Microsoft\Windows\Start Menu\Programs\

# Burp Suite Professional Installation steps for Linux
1. Open Terminal And Type
```bash
git clone https://github.com/Agellls/Burp-Suite-Lifetime.git
```

2. After Done Type
```bash
cd Burp-Suite-Lifetime
```

3. Now Type
```bash
sudo chmod 777 Kali_Linux_Setup.sh
```
```bash
sudo chmod 777 keygen.jar
```
```bash
sudo chmod 777 loader.jar
```

4. Now Donwload Burpsuite Pro With Type
```bash
sudo ./Kali_Linux_Setup.sh
```

# Burp Suite Pro Activation Steps
1. Modify License String like "license to cybercommunity03"
2. Copy License key from keygen.jar and paste in Burp Suite Pro and click Next.
3. Select Manual Activation Option on your bottom Right in Burp Suite Pro.
4. Copy License Request from BurpSuite_Pro and paste in Keygenerator.
5. Copy license response from Keygenerator and paste in Burp Suite Pro, then next and Done.


# Executing Burp Suite Profession after Activation

--> Windows :-: You can start Burp Suite Professional from Start Menu.

--> Kali Linux :-: You can start Burp Suite Professional by writing **burp** in terminal.

# NOTE IF U GOT LICENCE POP UP AGAIN
1. Just run
```bash
java -jav keygen.jar
```

2. And Repeat Process Activation Steps

3. After That Enjoy To Use Burpsuite Pro :)
