# In short
1. Create firebase project
2. Add firebase to Android app (google-services.json)
3. Enable firebase realtime database
4. Turn off firebase realtime database security rule, see code below:
    ```
    {
      "rules": {
        ".read": true,
        ".write": true
      }
    }
    ```
4. Copy the url of database, put in that code reference.

------------ end - modified by tfkproject ------------

# Let's Chat

A personalised android :100: chat application with your full control over it. :smile:

>**A fully completed app should greet you with a screen like this:**

![screenshot 2019-02-02 at 7 08 44 am](https://user-images.githubusercontent.com/41565823/52160668-36ff8a00-26ba-11e9-983e-2fbb40282b08.png)

**You can read the tutorial based medium post about building this app from scratch [here](https://medium.com/@pradyumandixit/how-to-make-a-personal-chat-application-like-whatsapp-fda6dd4bcb5b).**
