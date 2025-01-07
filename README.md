# RaftLabs

To run my project please follow the below steps:- 

1. Clone the Repository

2.  git clone “https://github.com/Balachandar1997/RaftLabs.git “

3. After cloning Install Dependencies 
   npm i

4.Install JSON Server

5.Run the JSON Server on port 3000

      json-server --watch db.json --port 3000

6.   Go to app.json file 
      
  
{
"expo": {
     "extra": {
      "apiUrl": "http://192.168.0.102:3000"
    },  
  }

To run the application
Please update the above apiUrl to http://10.0.2.2:3000 to run the app in Emulator
Or
 If it is physical device use this  http://192.168.0.X:3000   . here X is your local network IP

7. After the apiUrl change check it in the browser whether we  are getting the json object . If we get then

8. Then “npx expo start“ to run the application

Google drive link for my apk file 

https://drive.google.com/file/d/1glpgHwN_dotl8GFywKv4EgAEFhhK1CHD/view?usp=sharing


Note : need to run the json server locally and configure the right apiUrl in app.json 
