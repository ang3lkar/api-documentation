# Authenticate user

User is presented with an intro screen, prompting him to speak in order to signin. We'll use the (Azure's Speaker Recognition API)[https://docs.microsoft.com/en-us/azure/cognitive-services/speaker-recognition/home] to identify who is speaking.

We'll use three users, two to show that the system identifies the user correctly, and one who will not be registered in order to show authentication failure message.

-----
- Hey Workable, please let me in.

_System wakes up, bell sound is heard_

- **Hello Theodore**

_System shows Theodore's avatar. Ready to start conversation._

-----
