# FOodKings DBMS-Project
# TEAM- 4
TEAM MEMBERS AND THEIR CONTRIBUTIONS: 
S Venkata Ramana- 19bcs096 (Frontend & Backend) 
M. Sai Madhav Reddy -19BCS074 (Frontend & Backend) 
E. Harshith Kumar Yadav -19bcs041 (Frontend & PaymentGateway) 
CH. Aaseesh sumanth- 19bcs033 (Frontend & UI design) 
D. Abhinav- 19bcs040 (Frontend & UI design) 
B. Neelakanteswar -19bcs020 (Frontend) 
B. Vijay nayak-19BCS017 (Frontend) 
K.R.R. Yatheeswar - 19bcs045 (Frontend)

website address is "https://foodkings.herokuapp.com/"

Admin account details (generally any number of admin accounts can be created in our project but 
this is for the reviewing and testing purpose):
email: admin@foodkings.com
password: 12345678


and database will be in mongo cloud in one of our teammates account.



# If the project need to be run locally:

1) Go to the terminal in the Visual Studio code and type:

 "yarn install"

this will download all the node modules 

2) Add Menu.json into MongoDB Atlas import the data into database called "foodkings" (create it)
and collection called "menus".


3)go to .env file and over ther change MONGO_CONNECTION_URL value from our mongo cloud cluster
connection to "mongodb://localhost/foodkings"


4).Enter after connecting our downloaded source code with mongo db sucessfully enter "yarn dev"
 it will show sucessfull then the project will work in localhost in the port 3300 sucessfully.


5). now register 2 accounts in our website and automatically users DB will be created in mongo atlas.
Go to users account if nothing is ther in it just click refresh button .
there for which ever account one wishes to make they can change role : "customer"  to
role: "admin" then those accounts will automatically become admin accounts.


6). there actually 8 collections of databases but only menu.json needs to be imported into our 
Mongodb atlas and rest of the databases such as users,orders,offers,sessions etc ..., 
need not be created while using the website and entering data into the website that will automatically gets
created into the mongoDB .

for example in the begining there will not database such as feedbacks in the Mongo DB atlas but once 
we enter feedback form in our website ,feedbacks get automatically created in the Mongo database and also 
the feeback form detail which the customer entered will get automatically stored and from the admin side the 
all feedback page will be automatically updated so we need not worry.
