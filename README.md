
# master-and-slave-configuration-for-pc-to-raspberry-pi

**Step 1:
          Open the bashrc in PC using command**
          
 `sudo nano .bashrc`
          
**Step2:
          Copy and paste the command that give below in you PC:**
                    
                export ROS_MASTER_URI=http://yourcomputerIP:11311
                export ROS_IP=yourcomputerIP 
                
                
          Example:
                export ROS_MASTER_URI=http://192.168.62.239:11311
                export ROS_IP=192.168.62.239
                
                    
**Step3: 
          After finishing this source the bashrc:** 
        
         source .bashrc
##Example
![Alt text](https://user-images.githubusercontent.com/126165658/228292025-a5b3a850-acb6-4c61-892e-6b6c4aa6218d.png)

**Step4:
          Now open the bashrc from the raspberry pi in putty or ssh in terminal
          Copy and paste the command in the raspberry pi**
          
                export ROS_MASTER_URI=http://yourcomputerIP:11311
                export ROS_IP=yourraspberrypiIP
                
                
              
        Example:
                 
                export ROS_MASTER_URI=http://192.168.62.239:11311
                export ROS_IP=192.168.62.214
             
**Step5: 
          After finishing this source the bashrc :** 
        
         source .bashrc
         
         
  Now run **roscore** in *PC* and run **rostopic list** in *Raspberry pi*.
              
