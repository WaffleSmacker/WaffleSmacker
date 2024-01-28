# Setup Streamerbot
Created by [WaffleSmacker](https://www.twitch.tv/wafflesmacker) Make sure to leave a follow for more future tips!
<br>
![Waffle_Logo](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/47f02801-7a5d-4c9f-a9b7-04bb6d9bd968)
<br>


## Introduction

Streamerbot will allow you to do almost anything you can think of on OBS!
Your imagination is the limit (seriously).
<br><br>

## Prerequisites

- [OBS](https://obsproject.com/)  OBS Should be version 30 or higher!
- [Streamer.Bot](https://streamer.bot/)
<br><br>

## Step-by-Step Guide

I recommend also checking out the [official streamerbot startup guide](https://docs.streamer.bot/get-started/introduction)
<br>

### Download Streamerbot
[Download from this page](https://streamer.bot/)

Feel free to install the program anywhere.

Once you are finished open streamerbot!

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/c0277d93-6784-48ce-bce6-039e9b3078e2)

<br>

### Connect to OBS

Open OBS -> Click Tools -> WebSocket Server Settings.

1. Make sure "Enable WebSocket Server" is enabled.
2. Note to make sure the Server Port is "4455" and that "Enable Authentication" is unchecked.
3. Hit Ok!

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/213782aa-19b6-4f8f-92b6-1b1a11dc1cfa)
<br><br>
![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/5a8bf244-0c52-4de7-9d3e-4c293f2bcba2)
<br><br>
![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/c0426d28-d5d8-485e-9bb5-0c85943c8d63)

### Connect StreamerBot

Open Streamerbot and head to the "Stream Apps" tab.

Click the "OBS" tab.

Right click on an empty space and click "Add"

Make sure you are using OBS version 30 or higher.

Name: Anything is fine
Version: v5.x
Host: 127.0.0.1
Port: 4455  (should be the same as in OBS)

Enable "Auto Connect on Startup" and "Recconect on Disconnect"

Once you hit ok, you should see that streamerbot connects to OBS successfully by checking the "Connected" status on the bottom right part of streamerbot.

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/a786a001-43bd-4e8d-8743-b55d62a66848)
<br><br>
![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/67e43c13-8737-44b0-940a-3599dea76154)
<br><br>
![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/3b9b2fcd-dac8-4426-9852-5cf0dbf126a6)


### Connect your Twitch Account

Open Platforms -> Twitch -> Accounts

Click the Login button to connect your twitch account.

A window will open up to allow you to automatically connect your twitch account.

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/9fc4ba0e-acde-4d40-81ab-f0823937aebb)

Once completed you should see your account successfully connected!

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/88155698-e86b-4f34-bd82-3c9398cccc60)


### Final Test

Let's test to make sure StreamerBot is connected to your OBS and Twitch!

Copy the following string:
```
U0JBRR+LCAAAAAAABACNkz1v2zAQhvcC/Q+K5siQZNqysrlD27kp2qHIQJFHhwg/VH40NgL/95KSZUuWA2QRePce3yMfnt4+f0qS9B8Yy7VKH5LlfZfgstXG/Tqnyz4tueLSy0s+zRflokxPKjgccm8xCKHCEmLJT7AueXQGQmwa7frqUIC9e9YmlvzGjAl4lJi8gDnrl1OlxSJf5GeBgiWGt+4kbhMbzisgcbGT04nEL5BYb8Ln0jbhNiFaKSAOaFgZE1bicJdG02N/A4onN8AktrAh86fPJIPUyZzG7kuyXjUULbMlrlGGVlWdbaq6yjawWtcFQLPJ2XDybttfDz6CUV6IcR4UbgRET2c8TJQ9EZ7CV6Pld26dNodQxLCwk6qB94D6S7hzZD9pvjPat8OrcLWbiFi84oP94dUte4MV1XJLTtRnemBLfICq3C3VGb7bhfccs7zi2b85NjxiiIVvx/srtSfO8oKhKi+yDa5ZhjBCWVOgMqNNURK8alCDyvR6qzu0kU6Vl9fKu9xnTKI+lo+X4GnCcT43t+7qYO9GTzEe1rvZ+VsDDAJeuiVE+w5ycRsPQps14HWAUi1phtYFy3BThbBkYRRZU5OSzuxfge+eo2n4z95BV8yEYZiuJvkDVLmisI/dPo7zW2zWMX2ajp0QuLVAR/ognwyH+v7Pm1iE7VKGwZ4mHZenUe2sgs3xPwGIcEwoBQAA
```

Click on "Import" in StreamerBot.

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/75449e00-41ed-4895-9234-4b26832ed4d8)

Paste the code in the text box:

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/f9795f87-968e-4998-9b79-ac154ba020db)

You should now have a new Action in StreamerBot!

Click it -> Right click "Test" in the Trigger window -> click Test trigger

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/3814da7e-f3a5-4363-8ce6-faa544f7f748)

If the connection was set up correctly, you should see a message in your OBS!

![image](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/f43e6ca6-0f80-4583-b277-59984d062077)

Congratulations! You have now set up streamerbot!
