# lite
Gocroot Backend Lite Version

## Setup Server

![image](https://github.com/gocroot/alwaysdata/assets/11188109/3ba8a59a-61a3-4018-9aef-40e35ade12b1)  

Sign Up for a 100MB plan Free for life in [alwaysdata](https://www.alwaysdata.com/en/). Login into your dashboard and follow this instruction:
1. Open the menu Web>Sites>Modify
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/a95bce70-f0fc-4a74-abfa-51ba3dd543d4)
2. In the Configuration section edit command and Environment
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/d88f8fe6-08a3-4efe-9705-3ad5016b80ee)  
   Please set the environment variable in your system:
   ```sh
   MONGOSTRING=YOURMONGOSTRINGACCESS
   WAQRKEYWORD=yourkeyword
   WEBHOOKURL=https://yourappname.alwaysdata.net/whatsauth/webhook
   WEBHOOKSECRET=yoursecret
   WAPHONENUMBER=62811111
   ```
   In this menu, you will see an APPID in the title, shown as a number and a home folder used in the github secrets variable.
3. Go to menu REmote Access>SSH>Modify, set a very strong password and tick enable password-based login
4. Set APIKEY in Customer Area>Profile >Managing Tokens>Generate a token
5. Add sshhost, sshusername, sshpassword, sshport, apikey, appid and folder in your GitHub secret>action variable
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/5cc1e831-49d5-47d1-9486-d6f0f748a963)  


## Database
