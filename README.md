# InsReq
**InsReq** stands for "INStall REQuirements.txt"

**Description**
Easily auto-install Python3 dependencies from "requirements.txt" through Kali repositories using APT. 
(Example: python3-requests or any other python3-*).

**Advantages**
No need to use pip (and a Virtual Environment) to install python dependencies.
Instaling through APT makes dependencies available system wide.
Install everything quick just by executing InsReq from the directory where "requirements.txt" is.

**Installation**
```
wget https://raw.githubusercontent.com/ManuMeisen/InsReq/refs/heads/main/insreq && chmod +x insreq && sudo mv insreq /bin
```

**Usage**
First, make sure to be in the correct directory (where your "requirements.txt" is).

Then just execute:
```
sudo insreq
```
