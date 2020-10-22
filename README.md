# SSB

## Gym Equipment Sharing

This is a web application that is designed with the primary person of connecting people with 
gym equipment they are no longer using with people who wish to hire the equipment. The target 
for this shall be people requiring specific gear. People who want to take action on their health
at home without the outlay. Or people just looking to try different things to see what works for them.
All payments and hiring shall be done through the application. 


### Minimum Features

* Log in / Log out for
* Upload Profile /create
* Add equipment
* Search for equipment
* Hire equipment


## Wireframes



### Home page - Log in / Search for equipment / Sign up

![Login Screen](docs/wireframes/Login_screen.png)

basic log in screen with a header. An appropriate background picture etc

### Sign up page - fields to be filled out

![Signu Up Page](docs/wireframes/sign_up_page.png)

Page to sign up and register your information. More fields shall be added. 
But this will capture basic user information for storage. Implementation might 
be better as a pop up window

### Profile page upload photos change information, dashboard/summary 

![Profile Page with Dashboard](docs/wireframes/Sign_up_Page.png)

Page show user profile as well as edit option
This page shall also have a dashboard showing equipment currently on hire/to be hired
(hired equipment shall be grayed out and duration remaining for hire shown, equipment for hire
shall be clear)

Second dashboard shall show equipment on hire with monthly cost as well as duration remaining
Hires shall continue until equipment is returned. Incentives for longer hire durations can be included

### Product Page - User reviews, owner information, other products from this user, details about the product

![Product Page](docs/wireframes/Product_Page.png)

Page shows equipment to be hired with a hire now button. Also shows other equipment from that user and has an equipment 
star rating information on the equipment as well as rates for the equipment. Blurb on the equipment as well as photo's

### Search Page - After the user searches for equipment the following information is shown

![Search Page](docs/wireframes/Search_Page.png)

Users can see the equipment with photos as well as rates. From here they can get more info regarding the equipment, 
add to cart and receive notifications (equipment availability, hires running out etc etc )


## Installation

### Dependancies

Clone the repository from this github.

Create a Python3.8 virtual environment and activiate

In your console run the following:

```bash
python3.8 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

python3.8 main.py
```

## CI/CD

### Dev branch

The CI/CD for this project shall involved running automated testing using unittest, flake8 and mypy,
this shall be updated and altered as other tests or modules become more relevant. The CI pipeline shall push to 
Github. From there the application shall be deployed to an EC2 instance with an elastic IP. The application shall be 
tested on the EC2 instance for bugs manually before being rolled out to produciton

### Main/Master Branch

This shall be as above on a seperate EC2 instance that is conceptually ready as a server ready to run the app for public consumption





upload equipment button, search field at top.
Search results/filters/fields
Individual item summary page
checkout page
    
 






*Some ideas people can search for equipment from the start page, option to login in once they find stuff.
or can log in from the start.

Base Idea:

Someone can upload gym equipment for hire
Someone can hire gym equipment that has been uploaded for a period of time.


Other options.

