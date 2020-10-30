# hackathon
Khana Bachao ******DELHI edition*****
requirements: Python 3.7
              *FOR FURTHUR REQUIREMENTS CHECK "requirements.txt"*

Modules req to run this repository : 
pip install pandas
pip install tensorflow==2.0.0-alpha0
pip install Flask
pip install flask_sqlalchemy
pip install flask_migrate

Procedure to run:
1. change your directory to our folder "Dabba0"
2. Make sure you have all the requirements satisfied which are mentioned above.
3. while in this directory run * python viv.py *             //as viv.py is our main file

Workflow:
on noticing that local server has started running ,go to localhost:
http://127.0.0.1:5000/ on the browser.

1.you see a page where you need to enter your mobile number and then the otp which you will be receiving via way2sms api
2.You see a form for registering as an individual or as an organisation

#organisation 
as you land on our organisation signup page , you will be prompted to enter details such as your NGO name,NGO address,NGO pincode.
and on filling the form you will get a flash notification on ur brower on your successful registration , after which you will be redirected on our landing page.
#individual/caterer/client
aas you land on our individual signup page , you will be prompted to select from two buttons :1. Donate    2. Predict amount of food required for your event
$ Prediction:
on clicking predict button you will be redirected to a form where in you will fill details regarding your event which will then be processed by our prediction model to generate a good result for amount of various foods (chapati,rice,vegetable,daal) in Kgs .
now on clicking submit you will be redirected to the "prediction page" where quantities of foods to be cooked are displayed.
also here you get a button to go back to your homepage.
You now get redirected to a page where you can choose to either predict again to to "donate"
$ Donate:
on clicking donate button you will be redirected to a form where in you will fill details regarding your leftover quantities of food which will then be used to send details to the nearby NGO's of the same.
Message is sent to top 3 NGO's so as to avoid any clashes and mishaps.
now you get redirected to the home page. 
