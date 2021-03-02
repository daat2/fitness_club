## **PROJECT NAME: DAAT FITNESS-CLUB
*Final Project*
*Brand Name :  DAAT Fitness*
---
# **TABLE OF Contents**

* [**Project Concept**](#Project-Concept)

* [**UX** ](#UX)
    * [**User Stories**](#User-Stories)
    * [**Wireframe** ](#Wireframe)
* [**Features** ](#Features)
   * [**Existing Features**](#Existing-Features)
   * [**Features Left to Implement**](#Features-Left-to-Implement)
* [**Technologies Used**](#Technologies-Used)
    * [**Frameworks and libraries used in the project**](#Frameworks-and-libraries-used-in-the-project)
* [ **Testing**](#Testing)
* [ **Deployment**](#Deployment)
* [**Credits** ](#Credits)
    * [**Content** ](#Content)
    * [ **Media**](#Media)
 * [**Acknowledgements** ](#Acknowledgements)
 * [**Disclaimer Warning**](#Disclaimer-Warning)

---
## Project Concept
## Django Methodology (eCommerce)

The project is based on an eCommerce store to enable students to learn the web framework using Django along with Python3.
The concept of the project has enabled students to see the power of Django web framework in creating an app using models within a short period time.
My take away : The project is full of different technologies,components,it is not a stand alone app. In accomplishing the working project,
i have used Amazon S3 to display images in Heroku, google emails authentication, JSON to load products into the app ,Bootstrap classes,
Webhooks signals, Stripe payments and lot of packages installation up to deployment to Heroku.

My project framework is based on the Django milestone Project.I have used the project as my model, 
to enable me to fully understand in my own way and as backup for future reference.
The hands on experience achieved in the milestone project can be utilised in a work environment and can be developed further into a live store
if needed in the future,knowng the technology behind it is a plus,also the power of digital resources is growing as a result of global pandemic
the course contents are highly desirable.

I have also learnt the CRUD (Create, Read, Update and Delete) relation to database actions in the project.The CRUD was used throughout the entire project.
Overall objective of a Fullstack developer has being achieved based on the Code Institute Course modules.
Thank You.
  
 

 ## UX 
This project has been built with easy navigation menu for users to purchase from our store with ease,enabling a call to action.
No color blurring , it has a simple page layout, the process form placing order to checkout is streamlined.
I have incorportaed power of Bootstrap Toast for notifications so users can see their pop up messages
and preview order from their shopping bag.A top to back link click function was also created to enable users to get to the top of 
prodcuts quickly saves them from scrolling through all products.
Overall the User Experience process is smooth.


## User stories

**The objectives of the user stories is based around the CRUD functionalty for shoppers and prodcut management*
*to complete the end to end process of store purchases*

**User Story ( Persona : Jane gym lover, wants to keep fit.)**

 - As a Fitness Shopper: 
 *Objectives:* Purchase products,Register an account to join the fitness club,Sort and search products
  and complete purchase and checkout.

1. I want to be able to go onto your website shop and view list of all products.
   So that i can select a product to purchase.    
*Acceptance criteria*:Jane should be able to browse through the list of products on the shop fitness club site. 

2. View Specific category of products: So that i can  select each category menu such as *Active Wear*.
*Acceptance criteria*:A specific category can be find without having to  browse through all products.

3. View individual products details page: So that i can identify product price, images, and option for sizes if applicable.
*Acceptance criteria*:A Shopper can view the detail page and view the price, images and description.

4. Quickly identify offers,product bundles and special offers:	So that i can take advantage of savings.	
*Acceptance criteria*: A menu to display the specials is available to make informed purchases.

5. Easily view total of my purchase at any time:So that i can control my purchases and time .		
*Acceptance criteria*:A total cost view should be displayed in the shopping bag so shopper can see their bag items.

6. Easily register for an account: So that i can create a profile and view my order history.
*Acceptance criteria*: A shopper should be able to go to the Join button and be directed to profile page.

7. Easy login or logout:  So that i can login back to access my account and update my information
 and logout of account to protect personal information.
*Acceptance criteria*: A shopper should be able to login and logout of the shop.

8. Recover passowrd incase I forget :,So that i can reset my details when i forget	
*Acceptance criteria*:A forgotten password link should be visible, shopper should be able to click on the link.

9. Receive email confirmation after regsitration to join the fitness club:So that i can verify my email.
*Acceptance criteria*:	Shoppers should be able to receive emails confirmation .	

10. Create Profile:So that i can have a personalised user profile in order to keep track of order history.		
*Acceptance criteria*: Shoppers was able to make a profile page upon joining the club.

11. Sort list of available products in the ALL procucts menu : So that i can sort by best reated products.
*Acceptance criteria*: A shopper was able to sort by rating. 

12. Sort specific category of products :So that i can find the best price or best rated products
  in a specific category  and also sort products by category name.
*Acceptance criteria*: A shopper was able to shop by selecting any of the category name.

13. Sort multiple categories  of products simultaneously : So that i can find the best  price or best rated products
 across categories  such as shakes and bars.
*Acceptance criteria*: Shopper was able to shop simultaneous Products.

14. Search a prodcut by name or by description: So that i can find a specific product i like like to purchase 	
*Acceptance criteria*: A shopper was able to enter an input in  the search field by name or description .

15. Easily see what i have searched for : So that  i can see results quickly and make a decison on purchase.	
*Acceptance criteria*:A  shopper was able to make buying decision based on search results.

16. Easily select the size and quantity of a product: So that i can see the quantity and sizes of  selected product,
    and not to have selected wrong item or change my mind on selection.
*Acceptance criteria*: A shopper was able to see sizes and quantity of selected products.

17. View items in my bag to be purchased:So that i can identify the total cost of my purchases and all items in my bag. 		
*Acceptance criteria*: A shopper was able to see the total cost of products selected in the shopping bag.

18. Adjsut the quantity of individual items in my bag:So that i can make adjust itmes in my bag before i checkout.
*Acceptance criteria*: A shopper was able to make necessary adjustments before checkout.

19. Easily enter my payment information: So that i can checkout quickly.
*Acceptance criteria*: A shopper was able to enter payment information quickly.

20. Feel my personal information is save and secure.: So that i can feel secure about my payment information
*Acceptance criteria* : A shopper was able to click checkout securely link.

21. View confirmation after checkout.: So that i can see the order in my bag,other charges and verify i have not make mistakes.
*Acceptance criteria*:A shopper was able to verify items in bag and payment charges before checkout.	

22. Receive an email confirmation after checking out: So that i can keep information of my purchases.
*Acceptance criteria*: A shopper received an email confirmation to see payment charged and order paid for .	

**User Story (Persona Rose: Admin Store Manager.)**
- AS a prodcut manager(PM) :
 *Objectives:* Add,Edit and Delete products from the store 

23. Add a prodcut:  So that i can add new product to the store.
*Acceptance criteria*: The PM was able to add new product to list of Products

24. Edit/update product: So that i can edit product prices, Update description, available sizes and images.
*Acceptance criteria*: AS a PM, i was able to perform the update and edit functionality.

25. Delete a prodcut: Remove item out of stock.
*Acceptance criteria* : I was able to remove items not  available .

  

 
### Wireframe

My wireframe was designed with Balsamic software tool and imported to PDF for viewing. 
The document can be found in the folder path named Wireframe.
The wireframe was initiative was based on my initial planning phase as a mock-up  to show the  basic functionality of  the webpage and end users interaction on different browsers .
The final product of the webpage it’s slightly different due to additional requirements along the design phase.  I have used Agile Methodology as part of my project management 
 Click on the link to open the Wireframe.[**Wireframe DAAT FITNESS-CLUB**](https://github.com/daat2/)

# Features

## Existing Features 
*DAAT FITNESS CLUB* :

The  Existing Features are based on CRUD Functionality set out below :

 **Accounts: Join, login and logout page.**
* Are administrative task perform by users to enjoy the benefit of joining the fitness club as a returned customer. 

**Navbar:  Site Naviagtion menu.**
*  The Navbar comprises of all the navigation links which users will use to navigate through all the pages of the website
  to complete their purchases.Example users can click on All prodcuts and it displays all products.
* All the navigation menu are call- to- action to be performed by online users visiting the store page.#

**Profile page:**

* Users will be able to create a profile of themselves for easy purchases in future.  They will be able to 
add email address , phone number and set a password. A paasword can be recovered if forgotten to their registred email.

**Prodcut Manager Page: Store Owner:.**

* The Store owner can add  New,Edit ,Remove and Update image. End to End CRUD perform by store owner.
 
 **Shopping bag:**

* User can view orders added to their shopping bag.

 **Prodcut Detail Page:**
 
 * The summary of the prodcut can be viwed here, along with the prodcut description, quantity, price and any rating and can take action  
 to purcahse a prodcut.

 **Checkout page:**

 * Summary of items added to the bag , the total cost inclusive delivery if any,  and action to securely checkout to complete purchase.

**Email Confirmation:**

 * Confirms account registration.
 * Confirms orders purchased.
 * Confirms delivery information.


**Payment Card:**

* Takes card payment information of orders added to the shopping bag.
   
 **Social Media:**
 
 * Opens up social page for users to visit their social networks.

    
## Features Left to Implement
  
I am constrained by time, impediments and volume of the contents which limit my strength to provide more functionality to this project. 
i would have love to implement more accessible features for user of the site.This will be part of my work in progress in future.
 Aspiring ideas are :

**MailChip:**

* Ability to allow customers to subscribe to our newsletter for product offers.

**SITE Logo:**

* Fitness club site logo for users to recognise the brand.

**Digital products:**

Allow users to  download and print lesson pass in a digital format, saves them queuing up when they visit the fitness club,
especilay when they are running late for their gym lessons.

**Sales report: product management:**

* This will enable store owner to keep track of inventory and stock up.Also to see the trends of products users are buying.
* Store owner can  offer deals, clearance to boost sales of underperforming products.
* Sales graphs will give a glance of product health.

**Community meet up sessions and Social media success story:**

* A community based forum to encourage and motivate  users to come to the fitness club.



## Technologies Used

### Frameworks and libraries used in the project

* [**Python** ](https://www.python.org/dev/peps/pep-0008/)
   *  It is used to run the command line and the language used to work with Django . I have used the link attached as a reference guide in the project.

* [**Django** ](https://www.djangoproject.com/start/)
   *  The project is Django web framework , all models are based on django packages.

*  [**Stripe**]( https://stripe.com/)
   * The for regsitering payments
   
* [ **JavaScript**](https://www.javascript.com/)
    *  JavaScript libraries  and framework have been used to initialize my Navbar.

  * [**Json Formatter**](https://jsonformatter.org/)
    * I have used this site to build my fixtures for prodcut images.

 * [**Json Formatter**](https://jsonformatter.curiousconcept.com/)
    * I have used this site to validate my JSON
 
  [**Diffchecker**](https://www.diffchecker.com/)
    * Used for source code comparison.                   

* [**CSS**](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
  *  Used CSS to customize the styling  and customizing the page elements.

* [**HTML**](https://www.w3schools.com/)
   * I have used Semantic HTML Markup Language to write the project code,with some contents example picked from W3Schools site.

* [**Gitpod**](https://gitpod.io/login/?returnTo=https://gitpod.io/%23https://www.gitpod.io/)
    * Development Environment Editor for code and workspace.

* [**GitHub**](GitHub:https://github.com/)
    * I have used GitHub to create project repository and  for version control using Git functioanlity.

* [**Heroku**](https://www.heroku.com/)
    * Use to deploy and host app in a web browser.

* [**Balsamic**](https://balsamiq.com/)
    * A software design tool for mockup.I have used Balsamic to structure the basic functionality needed for my Recipe website project.
         
* [**Font-awesome**](https://cdnjs.com/libraries/font-awesome) 
    * It is a content delivery network imported for my CSS and Javascript libraries.

 * [**Bootstrap**](https://getbootstrap.com/ )
    * I have used the framework to design my social network link.
    * Used Bootstrap classes for styling.

* [**Amazon s3**](https://aws.amazon.com/)
    * To load images to connect to Django.

* [**Fontawesome Kits**](https://fontawesome.com/)
    * Used to generate kits for Icons to work properly.

* [**Codeinstitute**](https://codeinstitute.net/5-day-coding-challenge/?utm_term=code%20institute&utm_campaign=a%2526c_BR_IRL_Code_Institute&utm_source=adwords&utm_medium=ppc&hsa_net=adwords&hsa_tgt=kwd-319867646331&hsa_ad=417883010337&hsa_acc=8983321581&hsa_grp=62188641240&hsa_mt=e&hsa_cam=1578649861&hsa_kw=code%20institute&hsa_ver=3&hsa_src=g&gclid=Cj0KCQiAkuP9BRCkARIsAKGLE8UKGkHlbFcn5QITztlwWRaPBWLYQS9C51AIyuOS174_XD_nATSEj70aAnN7EALw_wcB&gclsrc=aw.ds)
     
    * I have used code institute models and libraries for this project.

* [**Markdown** ](https://guides.github.com/features/mastering-markdown/)
    * I have used this website to learn how to write my README Documentation.


## Testing
-----------------------------

Testing is carried out to verify the responsiveness and user friendliness of the site for end-users.
Test is carried out to ensure no broken links and users can complete their transactions and make seucre purchases.
The test is based on functional requirements as detailed in the user stories.

*Caution* :This test does not verify that webpage has a zero defects but can show it has defects and might not be find all defects.
as exhaustive testing is impossible.

See attached link for detailed manual testing preocess and defects report.


[Manual Testing](https://github.com/daat2/online-recipe-cookware/blob/master/static/testing/Daat%20Recipe%20Testing.pdf)

[Defect Report](https://github.com/daat2/online-recipe-cookware/blob/master/static/testing/Defect%20Reports.pdf)

* The project was tested on the different devices [IOS,Android, desktop and Laptop].

* The test was conducted across two browsers- Firefox and Google Chrome. 

* Used inbuilt lighthouse in google DevTools to audit  web app. 

* Operating System used for testing : Windows 8 and Windows 10.

* I carried out User Acceptance test by sending link to friends to test the navigation links and basic functionality.

* The part of the requirements for the test is based on the user stories in the UX header.


 
## Deployment
------------------------
The working project have been deployed to Heroku server as a running application.
Code is written in Gitpod and version controlled in GitHub.

* Heroku Deployment Steps:
* Assumptions Users has the following Accounts created :
    * Heroku account.
    * Files added and committed to git using git commands.  
    * AWS Amazon S3 Account.
    * Gmail for APP emails confirmation
    * Stripe for payments and webhooks.
    * Fontawesome to generate Kits.      
 
 ### Deployment steps: 
1. Created Heroku App with the App name.
2. Linked my  local Git repository to Heroku.
reated the app in Heroku.

1. After all the prerequisite:
On your Hertoku dashboard: >>> resources tab > provision a new postgres.
2. Back to gitpod >>> ```Install dj_database_url and pip3 install psycopg2-bainary```.
3. Then  ```pip3  freeze > requirements.txt```.To ensure Heroku Imstalls apps requirements.
4. Back to project level settings.py and import ```dj_database_url```. and replace the default database to call the
    ```dj_dtatbsse_url.parse```
5. On the terminal type in the command line ```python3 manage.py showmigrations``` (This will enable us to see all pending migrations)  
6.  Then run migration ```python3 manage.py migrate```.
7. Load your fixtures files start with categories first, then prodcuts(Load it in this order, beacsue products depends on categories)
            ```python3 manage.py loaddata categories```
8. Create a superuser to login.
9. Remove the Heroku Database config(To avoid URl not to end up showing in versoion control).

10. Use an ```if statement ```in the URL environmental variables in our project level settings.py.
11. Install gunicorn and freeze requirements.txt file .
12. Create a Procfile(Uppercase P)(This informs Heroku to create a web Dyno).
13. Temporarily disable collecstatic:
      ```` Login into Heroku on the terminal```
       ``` command line : Heroku config:set DISABLE_COLLECTSTATIC=-1 --app```
        This action will not allow Heroku to collect static files when our app is deployed.
14. Add allowed hosts in project level settings .py  and add a ```'local host'``` to enable gitpod to work .
15. Push to gitpod.
16. Go to Heroku app >>Deploy tab >>connect your database and enable automatic deployment.  
17. Generate a django key generator and add it to the reveal config variables field  in Heroku.
18. Back to project level settings .py replace the secret key and set it to get it from the environmental variables.
19. Set Debug to be True.
20. Commit  your changes and push to github.


## Amazon AWS s3 Deployment.

1. Log in to your AWS account.
2. Navigate to s3, and select create a new bucket.
3. Uncheck block all public access >>  select create bucket.
4. Turn on static webhosting, select the default values and save.
5. Make changes to the COORS configuration.
6. Go to s3 bucket policy tab, select policy generator and create a policy for the bucket.
7. Copy the ARN (Amazon Resource Name), paste it in ARN box and click generate policy and copy the
    policy in the bucket and save.

 ## Creating group policy om Amazon.

1. on the IAM (Identity and access management)>> create a group >> next a policy to attach to your bucket.
2. Import managed policy in the JSON tab >>paste your bucket ARN and create a policy.
3. Attach your policy to group and create user.
4. Download the CSV file and save it.( Contains Access and Secret key  ).

## Connect Django to s3
1. To be able connect django, two packages have to be installed 
```pip3 install boto3```
```pip3 install djamgo-storages```
2. Run the freeze requirements text file command.
3. Go to project level settins.py and add it to lisf of installed apps.
4. Define the AWS_STORAGE_BUCKET_NAME(To verify an environmental variable).
5. Go to Heroku and update all the environmental variables,
   and delete DISABLE_COLLECTSTATIC from the list of variables.
 6. Update the settings.py with the static files for production.
 7. For djandgo to upload images on Heroku app, a file called custom storages has to be created.
   >>create custom storages >>import settings from django config >>> create static storage classes
   >> update settings .py with URLS for static and media files.
   >>Upload all project images and save.
 8. Go to heroku app to open up the app.

**Project links**
 
[**DAAT Fitness Club)DAAT FITNESS-CLUB App in Heroku.**](https://daatfitness-club.herokuapp.com/)

[**Github Repository.**](https://github.com/daat2/fitness_club)

**Local Deployment**

### Steps for a developer to run the project locally.

   
Link sent to developer [**GitHub Link**](https://github.com/daat2/fitness_club).

- On the code tab,click the down arrow > Clone page displays list of clone methods.

- Select Https and copy the URL.

- Open Git Bash.

- Change the working directory to location where you want the cloned directory.

- Type ```git clone``` and paste the copied URL.(```https://github.com/daat2/fitness_club```)
  
- Press enter to create a local clone.

- Create your environment and import into the settings .py.

- Install the requirements text file.(In order to freeze your requirements)

- To run the project use the command 
   ``` python3 manage.py runserver```


# Credits
* Code Institute Django milestone project. 

## Content
 * I have endeavoured to write some of the code.
 * The contents of the page and images are taken from google search images.
* [** Django Secret key generator**](https://miniwebtool.com/django-secret-key-generator/).
 


|    <br>Website Sources    	| Project Ideas 	|
|-	|-	|
| [**Dietnow**](   https://www.dietnow.com/uk )                                                                       	| Ideas on Nutrition Products.           	|
|  [**Underarmour**](https://www.underarmour.co.uk)                                                                          	| Sport Prodcuts.  	|
|  [**EveryoneActive**](https://www.everyoneactive.com/)                                                                              	|  Gym activitiess ideas.       	|
|  [**Google**](https://www.google.com/)                                                                                	| Images for prodcuts                                 	|
|  [**myfitnesspal**]( https://www.myfitnesspal.com/ )                                                                               	|  Gym activities ideas.                                      	|
|  [**Cloudinary**]( https://cloudinary.com/)                                                                                    	| Design and upload Prodcut image properties.                	|
|  [**Code Institute Django Module(Mini PROJECT-Boutique-Ado)**](https://codeinstitute.net/)                      	| Used for code resources and ideas.                       	|
|  [**Tables Generator**](https://www.tablesgenerator.com/)                                                                         | Table generator.     
|  [**GitHub Docs**](https://docs.github.com/en)                                                                                	| Research on git documentation.


## Media
[**cloudinary**](https://cloudinary.com/)
* Used the resources to upload all project images.
 
* [**Codeinstitute**](https://codeinstitute.net/5-day-coding-challenge/?utm_term=code%20institute&utm_campaign=a%2526c_BR_IRL_Code_Institute&utm_source=adwords&utm_medium=ppc&hsa_net=adwords&hsa_tgt=kwd-319867646331&hsa_ad=417883010337&hsa_acc=8983321581&hsa_grp=62188641240&hsa_mt=e&hsa_cam=1578649861&hsa_kw=code%20institute&hsa_ver=3&hsa_src=g&gclid=Cj0KCQiAkuP9BRCkARIsAKGLE8UKGkHlbFcn5QITztlwWRaPBWLYQS9C51AIyuOS174_XD_nATSEj70aAnN7EALw_wcB&gclsrc=aw.ds)
    * Used some of the source code from my boutique_Ado mini project.    


## Acknowledgements

 I Acknowledged the support of  : 
* Neil kavanagh: CI Senior support.. Without him i wouldn't be able to complete this program.
i am indebted to him for his suport,understanding and empathy.I am greatful.
* Tim Nelson: My favourite Tutor .. Patience,calm and always ready to help.Thank You.
* Mark McGann: Student Adviser.. Thanks for your sympathy.
* To my unrelenting support tutors : I really appreciate their support and patience .. Johann, Igor, Cormac and Kevin.


## Disclaimer Warning
 
  The materials and sources used for this project are intended for Academic purposes only. 
