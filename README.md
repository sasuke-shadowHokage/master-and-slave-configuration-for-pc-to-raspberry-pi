
# master-and-slave-configuration-for-pc-to-raspberry-pi

**Step 1:
          Open the bashrc in PC using command**
          
 `sudo nano .bashrc`
          
**Step2:
          Copy and paste the command that give below:**
                    
                export ROS_MASTER_URI=http://yourcomputerIP:11311
                export ROS_IP=yourcomputerIP 
**Step3: 
          After finishing this source the bashrc:** 
        
         source .bashrc
##Example
![Alt text](https://user-images.githubusercontent.com/126165658/228292025-a5b3a850-acb6-4c61-892e-6b6c4aa6218d.png)

**Step4:
          Now open the bashrc from the raspberry pi in putty or ssh in terminal**
          
                export ROS_MASTER_URI=http://yourcomputerIP:11311
                export ROS_IP=yourraspberrypiIP  
             
**Step5: 
          After finishing this source the bashrc :** 
        
         source .bashrc
         
         
  Now run **roscore** in *PC* and run **rostopic list** in *Raspberry pi*.
              
