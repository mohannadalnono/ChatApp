# ChatApp
ChatApp using written in flutter by the help of firebase

(this app is realized as project of fin of studies of diplome DAI [development application informatique])

this is the feauters I am working on (planing sheet): 


Dart as backend language
Flutter framework for frontend ui
FireBase as DataBase backend (static ip address)
Plugins with flutter to add features


Done: 

* Make users(email,username,password, Random generated color)
* TextFields controlled (bad email formatted, email already used, weak password, username less than 4 chars )
* Login with email and password
* TextFields controlled (wrong email, wrong password)
* Send messages in one room as broadcast
* Display messages with name and colors of user who sent it (for group)
* TextInputField cases controlled (empty String or just spaces message)
* TextInputField decoration (empty and filled effected, hit label)
* User upload his photo (X and by default his photo is circleAvatar with his first name char He must upload)
* Display user photo with his message
* User has friends listed screen (after login) with his filiere group which is also tile at head of the list (as default tile)
* Email confirmation:
* Wait for user to be approved from admin(ESTO administrator with special app) 


TODO: (NOTE: willn't make them all, no Time!)
- Email confirmation:
  - Wait for user to be approved from admin(ESTO administrator with special app) 
  - Send confirmation message to email
  - ESTO administrator makes accounts for students (from another special app, or website)
     - Import from excel file
     - Insert them manually
- Approve new accounts request (with chosen filiere)
- If there is login with google account so must be responsible approve new users in filliers
- Login methods
- User choose his own color
- User sends photos in chat (image picker beside TextInputField then choose method: camera or lib) and store it in DataBase as file structure, in chat streamBuild check if it’s file display it
- HTTP messages control (error messages)
- In chat app check if message is link open that site in integrated browser 
- Messages Tiles (messages_bubbles) is clickable (for copy)
- Text responsive for most devices sizes
- Push notification with new messages arrive
- Add important messages notification effects for important messages
- Location and calculate distance for every user (Privacy problem?)
- Decoration 
- Light and Dark theme 




some Screenshots of app at the moment:



first screen: 
![Screenshot_1646953546](https://user-images.githubusercontent.com/61779813/157771467-486f5f59-4991-405a-adc2-77805c9e2c3f.png)



group chat:
![Screenshot_1646953560](https://user-images.githubusercontent.com/61779813/157771476-f55449ec-a8b1-406a-baf0-949eae314cce.png)



private chat :
![Screenshot_1646953571](https://user-images.githubusercontent.com/61779813/157771477-dbdd942a-1340-4668-97b3-6733ac77e132.png)


# Making account

switch to signup instead
![Screenshot_1646954414](https://user-images.githubusercontent.com/61779813/157771823-32370ce3-2f24-44bd-8e69-fdb6a8b78d6e.png)



enter informations
![Screenshot_1646954470](https://user-images.githubusercontent.com/61779813/157771828-0f092165-c9a1-4f8e-b201-82e45a432196.png)




from the second app (console panel app) approve or reject requests
![Screenshot_1646954490](https://user-images.githubusercontent.com/61779813/157771831-dc74bf70-67b4-4613-a2b1-f5b7ab44502a.png)
