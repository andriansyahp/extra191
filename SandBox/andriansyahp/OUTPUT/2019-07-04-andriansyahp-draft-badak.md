# '*BADAK*'       

Comprehensive walkthrough on how to use `Badak`.

### How to access `Badak`
- Tunneling, via `kawung.cs.ui.ac.id`  

    Since `Badak` (`badak.cs.ui.ac.id`) can only be accessed from internal of Universitas Indonesia, we need to do tunneling (i.e. accessing private network from public network by port forwarding). We can do this by accessing `Kawung` first (`kawung.cs.ui.ac.id`). 
    
    + PuTTY 
        In order to access `Kawung` and `Badak`, we can use PuTTY that we have prepared from the [Prerequisites](https://github.com/andriansyahp/extra191/blob/master/SandBox/andriansyahp/OUTPUT/2019-07-04-andriansyahp-draft-prerequisites.md) part.  

        For step-by-step walkthrough, you can follow the images below.
        1. Open the PuTTY program that you have installed in your computer. It will open up a **PuTTY Configuration** as shown in the picture below.  

            !['PuTTY Configuration' window.](https://github.com/andriansyahp/extra191/blob/master/img/badak-drafts/putty-config.jpeg).  
        
            In the *Host Name (or IP address)* field, input the `Kawung` host name (`kawung.cs.ui.ac.id`), as shown in the red box in the image above. In the *Port* field, leave it as like the default configuration, which is '22' as shown in the green box in the image above. For the *Connection type:* radio button choice, choose 'SSH' as shown in the blue box in the image above. After that, click the *Open* button as shown in the yellow box in the image above.

        2. After that, there will appear another window asking for your credentials (username and password). Enter your username of Universitas Indonesia's SSO account and its password, as shown in the image below.  

            ![PuTTY Kawung login.](https://github.com/andriansyahp/extra191/blob/master/img/badak-drafts/putty-kawung-login.png).  

            If your login is successful, your PuTTY window may looks similar to the one in the image above. 
        
        3. After the Step 2 above, you have entered the `Kawung` server. Next, we will go to `Badak` server.  

            ![PuTTY Badak login.](https://github.com/andriansyahp/extra191/blob/master/img/badak-drafts/putty-badak-login.png).  

            Enter ```ssh <username-SSO-account>@badak.cs.ui.ac.id``` then enter your SSO account's password, just like the one in the image above.  

            After successfully done this step, congratulations! You have successfully entered the `Badak` server. 

    + Terminal  

        1. Open your Terminal.  

        2. After you opened the Terminal, you can go to `Kawung` by entering ```ssh <username-SSO-account>@kawung.cs.ui.ac.id``` then enter your SSO account's password, as shown in the image below.  

            ![Terminal Kawung login.](https://github.com/andriansyahp/extra191/blob/master/img/badak-drafts/terminal-kawung-login.png).  

        3. After you successfully entered `Kawung`, enter ```ssh <username-SSO-account>@badak.cs.ui.ac.id``` then enter your SSO account's password, just like the one in the image below.  

            ![Terminal Badak login.](https://github.com/andriansyahp/extra191/blob/master/img/badak-drafts/terminal-badak-login.png).  

            After successfully done this step, congratulations! You have successfully entered the `Badak` server.

- Accessing `Badak` while connected to Universitas Indonesia's WiFi
If you want to access `Badak` while connected to Universitas Indonesia's WiFi, you can do like the way of the **Tunneling** part above but you can proceed to do the Step 3 by using PuTTY or Terminal. 
