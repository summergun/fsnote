# fsnote
Login/Registration(3rd Party): 
User has to login/register the app by using Google/Facebook for the authentication. WAP App will then need to authenticate requests to the backend API server
Add friends:(including friends request)
WAT users can add/remove friends by searching phone numbers/sending SMS/sending emails. (friends info can be retrieved from google/facebook Oauth response)
Open add friends-->add friends
Choose a friend from your Contacts or enter friends emails, then tap Send Request to your friend. 
After your friends respond to your request, friends will share with his/her locations with you automatically. 
Group Management: 
Create/edit/remove groups with name, descriptions and photo
Tab Create Group  to create a group and edit the descriptions. 
Add/remove friends from groups
Location/Map Management:
**Identify friends location in real time** (Possibly simulate fake locations)
Toggle UI maps, clocks
Switch the compass to view a specific person
User can label the locations such as HOME, WORK (friends/group should be able to view the label as well)
Trigger an alert/notification to groups or a specific user if I’m nearby.  (we will define the radius in order to send the notifications)
Chat--low priority
Backend:
Users API 
Location API
Groups API
