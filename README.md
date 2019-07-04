# ECE_Degree

For best results, open the file in Chrome. 


## On Mac 

1. Go to [nodejs.org](https://nodejs.org/en/) and download the LTS version for Mac. 

2. Go through the installer, and once complete, you can delete the installer.

      *The next steps are all done in Terminal*
      
3. When installation is complete, open the Terminal by pressing Command+Space to open Spotlight Search and entering Terminal then pressing ```ENTER```.

4. Enter ```node -v``` in the Terminal to verify that Node.js is installed correctly and to see the version of Node.js that was installed. Example: v10.16.0

5. Next, type ```npm install -g live-server``` and then click ```ENTER```

6. You should see ```live-server@(numbers)``` that will let you know it has been successfully installed. 

7. Go to the path where ECE_Degree folder is located: cd /____/ECE_Degree-master/ECE

8. Type ```live-server``` and click ```ENTER```. Your main browser will now display the contents of the folder ECE_Degree.

9. Click on ```Home.html``` to start.

## Warning: 
There is a chance the above installer will fail the first time. If so, do the following.
          *All instructions should be executed in Terminal*
1. Type 
     ```sudo npm cache clean --force```
     and then click ```ENTER```. It will ask for the administrator password. Type it in. You won't see the key strokes, but it is being typed. 
     
2. Type
```bash
     sudo npm update -g ionic
```
then click ```ENTER```

 3. Type
    ```bash
    sudo npm install -g live-server
    ```
    then click ```ENTER```
     
 The installation should now be complete.     
     
    

## On PC 

1. Go to [nodejs.org](https://nodejs.org/en/) and download the LTS version for PC. 

2. Go through the installer, and once complete, you can delete it.

      *The next steps are all done in Command Line*

3. Search cmd, right-click Command Prompt and choose ```Run as Administrator``` on the menu. Then tap ```Yes``` to allow CMD to run as administrator.
      
 4. Type ```npm cache clean --force``` and then click ```ENTER```.
     
5. Type ```npm update -g ionic``` then click ```ENTER```     
      
6. Next, type "npm install -g live-server" and then click ENTER

7. You should see ```live-server@(numbers)``` that will let you know it has been successfully installed. 

8. Go to the path where ECE_Degree folder is located: cd /____/ECE_Degree-master/ECE

9. Type ```live-server``` and click ```ENTER```. Your main browser will now display the contents of the folder ECE_Degree-master.

10. Click on Home.html to start.
