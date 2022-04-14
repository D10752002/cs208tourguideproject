

SOFTWARE REQUIREMENTS

SPECIFICATION

for

Tour Buddy

Version 1.0

Prepared by :

\1. Tadi Dinesh Kumar Reddy (200001075)

\2. Annavarapu Bhanuteja (200001004)

\3. Mudavath Bhanu Prakash (200001048)

\4. Rahul Raut (200001064)

\5. Ramakrishna (200001065)

Submitted to : Dr. Puneet Gupta

Sir

April 14, 2022

1





Contents

1 Introduction

[3](#br3)

[3](#br3)

[3](#br3)

[3](#br3)

1.1 Purpose . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

1.2 Intended Audience and Reading Suggestions . . . . . . . . . . . . . . . . .

1.3 Project Scope . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

2 Overall Description

[4](#br4)

[4](#br4)

[4](#br4)

[4](#br4)

[4](#br4)

[5](#br5)

[6](#br6)

[6](#br6)

[7](#br7)

2.1 Product Perspective . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

2.2 User Classes and Characteristics . . . . . . . . . . . . . . . . . . . . . . .

2.3 Product Functions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

2.4 Operating Environment . . . . . . . . . . . . . . . . . . . . . . . . . . . .

2.5 Design . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

2.6 UML diagrams . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

2.6.1 UML Activity diagram . . . . . . . . . . . . . . . . . . . . . . . . .

2.6.2 UML Use Case diagram . . . . . . . . . . . . . . . . . . . . . . . .

3 System Features

[8](#br8)

[8](#br8)

[8](#br8)

3.1 Description and Priority . . . . . . . . . . . . . . . . . . . . . . . . . . . .

3.2 Functional Requirements: . . . . . . . . . . . . . . . . . . . . . . . . . . .

4 Nonfunctional Requirements

[10](#br10)

4.1 Performance Requirements . . . . . . . . . . . . . . . . . . . . . . . . . . [10](#br10)

4.2 Security Requirements . . . . . . . . . . . . . . . . . . . . . . . . . . . . . [10](#br10)

4.3 Software Quality Attributes . . . . . . . . . . . . . . . . . . . . . . . . . . [10](#br10)

4.4 Business Rules . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . [12](#br12)

2





1 Introduction

1.1 Purpose

In our modern world almost everything is available on our ﬁngertips. Entertainment,

work or recreation all of which are easily accessible. One of the few areas however

that lags behind in development due to the sheer variety in destinations is travel. In

our age most people before going on vacation, plan their trip sitting on an armchair.

When to reach which place, how to reach that place, how long to stay and so on. . . .

However where as the information about hotels and transportation is well organized, the

information about the various places/monuments/resorts itself is not well documented.

To get information about each of them we have to rely on government websites, which is a

tedious job. Even if there are private websites they usually advertise limited information,

limited to only the services the provide at the location. So what our web app does is

it displays all relevant information about the place at a single place. This information

includes links to various hotel booking apps, a link to IRCTC for booking trains, phone

numbers and information about tour guides etc.

1.2 Intended Audience and Reading Suggestions

This SRS can be useful for developers, project managers, users and testers. The docu-

ment will provide in detail the working of our Site ’Tour Buddy’ .

1.3 Project Scope

Our website creates a speciﬁc webpage for each place and takes in reviews from the

customers and adds them to it. Our project singlehandedly covers the job of providing

detail analysis of various destinations and how to reach them, where to stay and whom

to take as a tour guide. There our other miscellaneous features such as tour buddy in

which if a particular place is far from urban areas you can choose a travel companion so

as to reduce the taxi fare. There is also the nearest atm feature which helps in ﬁnding

ATMs nearest to you. The app also has nearest restaurant feature. All in all the project

decreases the burden on the tourist by not making him surf a lot of websites to get

information and thus helps in convenience of travel.

3





2 Overall Description

2.1 Product Perspective

Tour Buddy is a web-based service platform to create a community of travellers and

provide everyone a detailed account of every tour spot. Content creators will get a

chance to monetize their passion for travelling . The platform gives security to lone

travelling and distributes travelling cost, by grouping with other veriﬁed lone travellers.

2.2 User Classes and Characteristics

Tour Buddy has the following Users:

• Customers: Use services of searching and creating packages, pairing up, etc.

• Travellers: Search for places to visit without login from the website

• Maintainers: Maintain the website and add data

2.3 Product Functions

The product provides detailed information of all tourist spots, allows the user to create

his custom travel package depending on his budget. When in the travel he/she can get

all necessary details and things to do at that place. Also, customers can pair up or group

with other veriﬁed travellers.

This is done by matching up the requests for pair-up based on the dates and to and from

cities. Any sensitive information of the users is not displayed during the request of the

pair-up too.

2.4 Operating Environment

The platform is a web-app and requires any browser as the only support (the latest

version is appreciated). Thus, the product works across all operating system with the

requirement of a browser.

4





2.5 Design

The product is designed such that the data ﬂows from content creators to the users. To

use the portal every user the user has to create an account and ﬁll in personal details

during the ﬁrst login. They will be assigned a unique username and password.

Customers can login and search for the details of a tourist spot (famous for, travellers

visiting, things to take with you, etc). Once on travel he can access the nearest ATM,

transport spots, police station, etc.) according to their real-time location. They can

book ﬂights using customization and also pair up with other travellers to distribute cost

and ensure safety (Tour buddy feature).

5





2.6 UML diagrams

2.6.1 UML Activity diagram

Figure 2.1: Activity diagram

6





2.6.2 UML Use Case diagram

Figure 2.2: Use Case diagram

7





3 System Features

”Tour Buddy” is making a tour around the world with all the facilities at low prices.

The main purpose of this app is show them all the unknown tourist places.

3.1 Description and Priority

”Tour Buddy” has many main and some sub-ordinate features.The Highlight features:

The features with priority up to down -

\1. Searching for a tourist place and familiarizing with the history of the place and

making note of all the things to do around that place.

\2. Providing the user with emergency contacts and locally available tour guides.

\3. User can search for nearby transport Facilities and public places using Google

Maps.

\4. Providing Books and Magazines, videos on the tourist spots.

\5. User can search for nearby ATM,Bank,hotel,restaurant and Govt Oﬃces in our

app using Google maps.

\6. Pairing up users to cut down costs and ensure security during travel (Tour buddy

feature)

3.2 Functional Requirements:

User Veriﬁcation: Anyone can visit the website and can search the tourist places

which he likes, we will refer to such a client as a user. While some users will register on

the site and their email and mobile number would be veriﬁed using an OTP (one-time

password) system. These users referred to as Veriﬁed users will have certain special

privileges.

Tour Planning Features:

\1. Search For Place And Make Your Tour: Users can query the website to get

famous tourist spots ﬁltered on the basis of location (country, state etc), genre (histor-

ical, sightseeing, wildlife, hill station, etc.), budget, ratings, connectivity, etc. The site

will return a list of spots links based on the search made.

8





Allow the tourist to explore the spot to the fullest, before they make their ﬁnal decision,

by providing link to magazines and books to brief the user of the location.

2.Description, estimated cost, Duration of tours: Users will be able to extract

the description, estimated cost and approximate duration of their trip once they have

created a custom tour or selected a package oﬀered. Also they will be provided a route

of travel along with famous places on the way or nearby which they may consider to

have a visit to.

4.Pair Up/ Group up: In case the user is in search of company, then if both the

people agrees then pairing of the people will be accepted and done with in 2 days.After

that they can travel together.

Location-Related Features: After taking the location either manually or automati-

cally (with necessary permission) the user will have the following options:

Transport Details: User can get access to the nearest Airport, nearest Train Station,

nearest Bus stops and Cab station from Google Maps.

Nearest Facilities Details: User can get access to your live location on the map

which will show user the nearest restaurants,lodges, ATM’s and Banks,PS,Tourist Info

Desk and other leisure and entertainment as per the demand of the user.

9





4 Nonfunctional Requirements

4.1 Performance Requirements

The Tour Buddy website will be used for reciprocating all the needs or necessities re-

quired by any tourists planning to have a relaxed and secure tour, providing a smooth

user-friendly interface supported by MongoDB database.

4.2 Security Requirements

The system is secure and protects all personal information of the user unless given con-

sent (for the tour buddy features if at all). The system uses cookies which are stored

in the clients browser and not accessible by anyone outside the system. Each registered

user can only change their own information and not alter any other users.

4.3 Software Quality Attributes

The software quality attributes are explained in detail below:

\1. Eﬃciency: The system will be implemented using MongoDB database and coded

in a highly structured manner using Flask, jQuery along with MongoDB database,

since the software is aimed to be hosted in a website, it won’t be wasting any mem-

ory or processing cycles of the user’s devices.

\2. Maintainability: Since the system is implemented in HTML, CSS, JS, and Flask,

all the ﬁles are highly ordered and easily read by any developers in the future and

can easily pick out a particular feature to modify, since the frontend and backend

of the system are separated it shall be easy for the system to evolve as per the

customer’s needs and changing requirements. It is very easy to implement this as

it also ensures to minimize the costs required to change the software as the new

updates need not be manually installed in each user’s device.

\3. Dependability: Since the system uses the highly reliable cloud software Mon-

goDB, all the user’s personal or conﬁdential information is stored securely and

10





proper fail-safes shall be enforced to secure the database in any event of a crash of

the software, thus making sure it won’t cause any physical or economical harm to

both the users and the developers. MongoDB ensures high security, by ensuring

proper encryption and even IP access listing to make sure the database is only

accessed by the admin, and once connected to the cluster, the developers do not

need to physically access the data to make changes.

\4. In time: Proper work division and teamwork can assure the software is developed

with a properly working implementation of all features within the intended time

\5. Functionality: The system shall perform all the necessary tasks required by a

user intending to access the services of a proper tour guide, by the automation of

several features, the system oﬀers easy access to resources for the user to properly

plan the intended tour, minimizes the budget of the user, oﬀers several alterna-

tives and suggestions based on reviews, also has several features to access all the

necessary facilities to facilitate safe and secure travel.

\6. Adaptability: The system is easily maintainable and due to the highly ordered

implementation of the software it is very easy to access and change only the nec-

essary ﬁles even in the absence of the original developers in case of a change in

requirements of the software.

\7. Acceptability: The system shall be user-friendly, and designed after intensive

discussion of all features, and ease of operating the software. The system is also

highly compatible and does not require any modiﬁcation of the user’s current soft-

ware in their devices. All the features are properly described so that any user even

without prior knowledge of the working of the system can easily understand and

use the system’s features to access resources.

\8. Portability: The system is highly portable since it can easily be modiﬁed into a

diﬀerent language, the database handling, backend design, frontend design is im-

plemented in diﬀerent ﬁles and folders it is easy for any developer to access certain

ﬁles and convert them into a diﬀerent language and use the rest of the design with

minimal modiﬁcations.

\9. Scalability: The system shall be implemented with a good base and core func-

tionalities, and shall easily adapt as per the user’s demands.

\10. Understandability: The system is easily understandable by the users and de-

velopers alike, the developers can pick out the necessary parts of the program and

11





modify it with ease if required.

\11. Testability: Since the system is designed in a highly ordered fashion, it is easy to

ﬁnd or isolate any bugs or faults of the system in a particular part of the software

and modify only those ﬁles without disturbing the rest of the program. It is thus

highly testable.

4.4 Business Rules

Our TOUR GUIDE website is for helping any tourists to have a hassle free trip to a

tourist location.

Helps save precious time and minimizes the economic cost for the client. A lot of

these features have never been seen together in a single working software, thus is highly

proﬁtable ﬁeld too.

12


