# EcoSnap Mobile Application 

EcoSnap aims to collect real-time citizen participation in the determination of environmental and health problems during the creation of urban planning.

Enables to report an array of incidents including, but not limited to:
- Weak Eduroam
- Environmental Pollution
- Bad Sidewalk
- Electrical Problem
- Wrong Parking
- Waste
- Other Problems

You can downloay EcoSnap from [Google Play](https://play.google.com/store/apps/details?id=com.ecosnap.app) freely.

# EcoSnap Mobile Architecture 

![architecture](https://github.com/ilyascokan/EcoSnap/blob/main/Architecture.jpg)

# User Information Request
##  URL
https://peer-review.hacettepe.edu.tr/v1/api/account/login
##  Parameters
```json
{
  "email": "*****@*****.com",
  "password": "********",
  "pushToken": "anystring"
}
```
##  Method
POST
##  Response
[Login Response Example](https://raw.githubusercontent.com/ilyascokan/EcoSnap/main/1%20LoginResponse.json)

# Friends Activities Request
##  URL
https://peer-review.hacettepe.edu.tr/v1/api/activity?IdForFriends=d6483dea-e83f-48f8-9791-e95006e555bf&PageIndex=1&PageSize=1000
> __Warning__
Update IdForFriends parameter with your user id : $\color{red}{\textrm{d6483dea-e83f-48f8-9791-e95006e555bf}}$
##  Method
GET
##  Response
[Activities Response Example](https://raw.githubusercontent.com/ilyascokan/EcoSnap/main/3%20ActivitesResponse.json)

# User Project
- Download the EcoSnap application to your Andriod phone
- Make friends
- Create activities
- Fetch your records using the above methods
- Create a map project in any language and display these records on your page using any map library you want. (with location and photo information)
