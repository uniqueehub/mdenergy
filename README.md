# mdenergy

Steps for installation
Step 1 : Extract the mdenergy.tar.xz file in your desired folder present in my repo.
![step 1](https://github.com/user-attachments/assets/42d76614-c746-4ffa-96ec-8a7d1f27909e)

Step 2: Open terminal in src folder and enter the command “make linux”.

![358880793-a8d23faf-4899-4d1d-b2cb-276e3ede83bc](https://github.com/user-attachments/assets/249869b1-009b-44a9-89a7-66522b4ea7bf)

If you get the output below there is no error enjoy life.
![358880799-2c53edc6-9653-4f29-adb7-8dd94bed3618](https://github.com/user-attachments/assets/a9a2179a-f10d-41ba-b250-471bb58b0038)

Step 3: Enter the command in terminal “mkdir -p ~/vmd/tcl”
Step 4: Enter the command in terminal “sudo make install”![358880805-beb540ef-24dd-4de4-84e0-a28c0888b01e](https://github.com/user-attachments/assets/7b3a41c2-7c97-46d8-b8f9-1191f2af4f2a)

If you got the output below then the installation is done and do your stuff my debugging is done![358880814-df923261-37ac-438a-9797-b11422825ae5](https://github.com/user-attachments/assets/8e24df59-1457-47c1-8d00-803b206c521b)

Edits Made in src folder:
If you want the details of the errors solved its just replacing

```
#include<iostream.h>
```
with 
```
#include<iostream> 
using namespace std;
```
In each file present in src folder 
Also replace 
```
#include<iomanip.h>
```
With 
```
#inlcude<iomanip>
```
Add ```#include <cstring>``` in Energies.C  
Add ```#include <cstdlib>``` in hbondpsf.C  
Replace ```#include<new.h>``` with ```#include<new>``` in ResizeArrayRaw.h	
