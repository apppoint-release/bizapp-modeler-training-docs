## The Enterprise Workspace
Before initializing BizAPP Studio Modeler, let us become familiar with the development environment and the elements that constitute the Enterprise Workspace or the UI. 
_BizAPP provides the solution developers with two environments:_

1. The Modeler and 
2. The Web-client

### Modeler
Developers can use the activity based approach to develop the application. Within an activity, the Enterprise Model for the application is first planned and then integrated in the modeler.
1. **Enterprise Explorer**: This is a work-area on the left-panel that visually displays all the elements required in the application. Within an application, you can create an Enterprise model. All the elements or the artifacts that you define or create in an application, the Business Unit, Business Module, Business Object, Fields, Application, Application Category, Process Definitions, Mappers, Queries, Reports, Views and ViewDef’s will be listed under the Enterprise Explorer tree. 
2. **Application Explorer**: This is a work area within the Enterprise Explorer that visually displays all the elements required in the application. You can select the tabs to switch between Enterprise Explorer, Application Explorer and the Favorites Tab. 
3. **Activity Window**: The Activity Window manages all the recent changes made within an Activity. 
4. **Status Window**: Shows the current status of all the elements created in the Modeler.
5. **Recent Items:** Shows artifacts/elements that are currently created in the application.
6. **All CheckedOut Objects:** Displays artifacts/Elements that are checked out within an Activity or an Application.

### Web-Client/LocalHost
All the changes done in the modeler has to be published on the web-client. The run-time Enterprise for the client Modeler has to be configured for publish. Users can view the solution as a web-service which can be accessed using the Uniform Resource Locator.

#### Terminologies Used 
+ **Activity**: It is a collection of changes that addresses a specific requirement in the solution that is modeled. It holds or records a set of files that a developer creates or modifies during development. A set of files belonging to an activity is called a "Change Set". An activity allows multiple users to work on the same project.
+ **Enterprise**: It represents an organization's mission, functions, processes, and information flows. An Enterprise forms the origin of the hierarchy and can be used as reference for constructing all other models. An Enterprise can contain multiple Business Units.
+ **Business Unit**:It is a segment of an organization that represents a specific business function. For example, Sales, Purchase, Accounts Departments or Divisions form the second level of hierarchy in an Enterprise. Each business unit can be planned independently from the other business units of the organization.  A Business Unit can have multiple Business Modules.
+ **Business Module**:It is a segment of a business unit that represents a specific business process. For example, the warranty details of a product are managed by the Sales Department. Similarly, the transaction details of a client or customer are managed by the Accounts Department. 
+ **Business Object**:They are the core entities that help in the development of business management solutions. They represent real world things such as employees, products, invoices, or payments.  For example, a product warranty entry form needs to work with concepts such as customer details, product details and invoices. Each of these may encapsulate all the data and business behavior associated with the entity they represent.
+ **Business Field**:It is associated to a business object and assists organizations to identify and manage information critical to their business. Fields are the basic elements that take part in the creation of a business process and can be imported from external providers. Fields are also used for creating forms, queries, reports, and charts.

### Activity Based Development Approach
Within an activity, user may include changes in a data model, UI, security model, work flow and automation. With integrated activity based development approach, all the changes made in the context of an activity are deployed/delivered as opposed to individual changes. Every Activity goes through a work flow which is the life cycle similar to the Software Development Life Cycle (SDLC). 

#### Work Flow States of an Activity 
The Activity Based Integrated Development of BizAPP includes a version control infrastructure that controls the management of changes going to the solution model where multiple users can model different aspects of the solution in parallel and validate them as a change set. 
The approval process in an activity enables organizations to ensure that all the changes are validated as per requirements, before it can be deployed to the production environment.
 Figure { Work Flow States of an Activity}
 
### Initiating the Modeler
In this section, you will learn to set-up the modeler environment. This is a one-time setup to configure where your solution models are/or will be stored. A local or a centralized license server URI needs to be set-up for the modeler. 
To open the BizAPP Studio Modeler:
1.	Double-click the BizAPP Studio Modeler icon (shortcut) OR
2.	In the BizAPP folder of your local build repository, double-click on BizAPPModeler.exe file. 
The BizAPP Studio-Modeler window appears on screen.
 
3.	Click  Add , enter the path of the repository (empty) folder where the solution models are stored or where the solution models will be downloaded locally. 
4.	Provide a local or centralized license server URL that is needed to set up the Modeler. For instance, BizAPP can be accessed using the 13.71.71.190:13333
5.	Click Next to proceed to creating or downloading the Solution Models from the remote repository.

### Solution Models                                                                                                                                                                                                                                                                                                                            
Solution models have the basic infrastructure or the prototype of an application that is necessary to build or develop an application. You can use sample base models of the solution to build or develop the application. 
Using your account in BitBucket or GitLab, you can: 

+ Create a new Solution Model  
+ Download a Model from the Server
+ Connect to an Existing Model 

### Create a new Solution Model
A new solution model will be available for application development.  User has to be a repository Admin and should be given the required license to create a new solution model. The client connection to the modeler is not required when setting-up the modeler. This is a one-time activity.
To Create a new Solution Model:
1.	In the **BizAPP-Studio Modeler** window, go to **What do you want to do today?** section.
2.	Select the **Create a new solution model** option from the list and click **Next**.
3.	In the **Sign into your account** section, enter your credentials to sign into your account and validate your access to a solution model.
--- 
Figure: SignIn to BizAPP Studio-Modeler
---
4.	If you are logging in to the Modeler using the credentials of your BitBucket account, select the **BitBucket** Tab. 
5.	Enter your Bitbucket **Email ID, User Name** and **Password** in respective text boxes and click **Next**.  
6.	Otherwise, select the **GitLab** Tab to login with your GIT Lab Credentials. Enter the **Email ID/Username** and **API Token** (created for your GitLab account).
7.	Click **Next**. A **Download existing or Create a new solution model** window appears on screen. 
8.	In the **Select an empty repository to create solution model** text box, click on the drop-down and choose the **Solution Model** from the list.
9.	The selected model will get cloned locally into the path folder provided by you. Click Finish. The BizAPP Studio-Client window appears on screen.
10.	Since the client set-up is not required, in the BizAPP Studio-Client window, click Cancel. The BizAPP Enterprise Modeler is loaded on screen.

The **Activity Manager** window is open where user can either **Start a new development activity or  Continue Ongoing Development Activity**.

>NOTE: After working on the activity, you can CheckinAll your changes. When publishing your changes, you can cancel the connection to the Client Modeler.

## Download a Model from the Server

The option “Download a Solution Model” from the Server is available if user has the necessary permissions to access the repository and the license to download the solution in to the local repository on your system. 
To download a Model from the Server:
1.	In the BizAPP-Studio Modeler window, go to “What do you want to do today?” section.
--- 
Figure: Download a Model from the Server
---
2.	Select the Download a model from the server option from the list and click Next.
3.	In the Sign into your account section, enter your credentials to sign into your account and validate your access to a solution model.
--- 
Figure: Sign into BizAPP Studio-Modeler
---

4.	If you are logging in to the Modeler using the credentials of your BitBucket account, select the BitBucket Tab. 
5.	Enter your Bitbucket Email ID, User Name and Password in respective text boxes and click Next.  
6.	Otherwise, select the GitLab Tab to login with your GIT Lab Credentials. Enter the Email ID/Username and API Token (created for your GitLab account).
7.	Click Next. A Download existing or Create a new solution model window appears on screen. 
 
Figure: Download/Create new solution to Empty repository
8.	In the Select an empty repository to create solution model text box, click on the drop-down and choose the Solution Model from the list.
9.	The selected model will get cloned locally into the path folder provided by you. Click Finish.
The BizAPP Studio-Client window appears on screen to establish a connection to the client server. Refer: Login to BizAPP Studio Client for more details. 

>NOTE: If you are creating a new repository (from personal account) in BitBucket, or creating a new solution after downloading it to the local repository then the product should be added to the license. 

## Administrative Set-up
Since changes are done within an activity in the modeler, the new activity has to be associated with the application. It has to be integrated with the release (sprint/defect) for which it is being worked on. 
An Administrator has to configure a release (sprint) and an application to start work on a new activity in the modeler. Both the configurations are done by opening the modeler without an activity. 

**To Create a Release Sprint:**
1.	Login as Administrator. 
2.	In the BizAPP Studio-Client window, select Cancel/Continue. All the files of the solution repository will be loaded into the Modeler.
3.	In the BizAPP Studio Enterprise window, select the Admin menu. 
4.	Click Create Release Sprint, a Release Sprint window appears on screen. 
5.	Enter the name of the sprint from (pqube/Jira) for which the activity has to be associated. A new release sprint is created in the modeler.

**To Add a New Application:**
1.	In the Admin menu, click Create Application. OR
2.	In the Enterprise Explorer, right-click on the Application, and click Add New Application. 
3.	In the new Application window, enter the name of the application, for instance, RecruitManagement in the Application text box. A new application is created in the Modeler. 
4.	To close and exit from the Modeler, in the BizAPP Studio Enterprise, click Close button. 
You are now logged out of BizAPP and the modeler is closed.
A set of Application level attributes – Views, API’s, Screens, Code Libraries, Themes, Master Views and View Definitions are available under the new application.

**To Set-up the path for Publish:**
When working on the main database of the application, you have to establish a connection to the user database to publish your changes.
1.	In the BizApp Modeler landing screen (without an Activity), go to Tools menu. 
2.	From the Tools>>Options menu, select Publish from the options listed on the left-panel. 
---  
Figure 1: Publish settings on User DB 
---
3.	Under the Test Publish Options, Package Reference Enterprise text box, enter the name of the User Database. Here, it is Recruit_U/ Recruit_User.  
4.	Select the Enable Online Test checkbox to allow testing of the solution on IIMS publish/localhost set up for Modeler on your system.  
5.	Select the Do not publish personalized objects checkbox to disable the publishing of your persoanlized objects and Click OK.  
Now, all your changes will be saved and published to Recruit_User/Recruit_U. 

### Roles and Responsibilities
The role template and responsibilities required to access the Modeler are as below.  

| Role         |  Responsibilty           |  Description                             |
| -------------|------------------------- | -----------------------------------------|
| Admin        | User Administrator       | User Administrator                       | 
|              | Activity Packaging       | Manage Activity  				         |    
|              | Impersonator             | Allows user to impersonate other users.  |      
|              | Activity Manager         | Can publish an Activity 			     |
|              | Approval Manager         | Can approve an Activity 			     |
|              | Field Picker             | Allows user to add fields 			     |
|              | UI Manager               | Allows user to add Control Templates     |
|              | User Management          | User Management      				     |

## Login BizAPP Studio-Client 
You have to establish connection to the client or the application modeler by logging in to BizAPP Studio-Client.
1.	Double-click on the BizAPP Studio Icon   . OR
2.	In the local repository, open BizAPP folder and click BizAPPModeler.exe. This opens the BizAPP Studio-Client login screen.
3.	In the Enterprise text box, select the enterprise Recruit_User from the drop-down list. 
--- 
Figure 3: Login Enterprise BizAPP Studio-Client
---
4.	In the Sign-on service, select BizAPP from the drop-down and click Next to proceed to the next step.
--- 
Figure 4: Login - Enter username and password
---
5.	The **UserName** and **Password** should be admin in respective text boxes. 
6.	Click **Login**. This opens the BizAPP Studio Activity Manager window, where you can start a new development activity or continue with an ongoing development activity.

### Start New Development Activity 
A new activity is created in the context of a new application where you can begin your work on the Modeler. An activity has to be associated to the release (where the defect is filed) and the application you are working. 
To create a new Activity, follow the instruction as below.
1.	In the **Activity Manager** window, click on the drop-down of “Select the release where the activity would be delivered” option.
2.	Associate the activity to the Release where the activity would be delivered. On the drop-down, select the release (sprint where defect is filed).
3.	Select the name of the application you want to work on from the drop-down of “Which Application do you want to work-on?” option.
4.	You can either start working on a new activity or continue working on your current activity. Select one of the option in the “What do you want to do today?”
5.	To create a new activity, select the “Start new development activity” option. Other options will be available as below. 
6.	Add a brief description about the development in the Select/Fill-up the Requirement to be developed text box. This description will appear as the name of the activity.  
7.	If team has other developers working on the same application, then select the “Allow others to co-develop” checkbox, and click Open.  
The BizAPP Modeler, landing page is open on screen. 

### Application Category
Similar or related applications can be grouped based on categories or on their functionalities for easy retrieval. Basically, users can create different applications corresponding to various clients and group those under the parent category. For Instance, An “Application Category” could be “Healthcare Services”, under which applications specific to healthcare could be created and associated to the category accordingly.
To create a new Application Category, do the following:
1.	In the Enterprise Explorer, right-click on the Application Categories, and select Add Application Category option.
 
Figure 6.1: Adding Application Category
2.	In the Add Application Category window, enter the Name of the new category as HRIS.

>NOTE: The name of the Application Category should be unique as many users will be working on the same database.
---
Figure 6.2: Adding Application Category
---
3.	Click OK.  You have now created a new application category and it appears in the Explorer window.
4.	When you add new element in an application, it will be in Edit or Checked Out state by default. Select CheckIn to save the changes in the current element. 
5.	Right-click on the Application Category HRIS, and select Publish.
 
 Figure 7.1: Publishing Application Category

#### Associating Application to Application Category
The listing of application under categories is possible only if it has been associated to its respective category. 
To associate the application Recruit Management to HRIS category:
1.	In the Enterprise Explorer, expand the Application Categories to open the HRIS category. 
---
Figure 7.2: Application Categories
---
2.	If you are associating the application immediately after the creation of the category HRIS, then the category will be automatically checked out.  Otherwise, right-click on HRIS and select Checkout.
3.	Open the HRIS Category to view its details. The window shows the list of applications associated under this category. 
4.	Click  Add icon to open the Enterprise search window. Select the check box corresponding to the application to be added, and click Associate. 
The newly created application is now associated to the application category HRIS as shown in the figure.  
---
Figure 7.3: Associating the newly created application to the respective category
---
### Save your Activity
Your changes will not be saved, if you close the modeler without saving your activity. A CheckIn and CheckIn All options can be used to save your current changes. 
a.	CheckIn: Saves your changes on the Business Unit, Module, Object or Field that you are currently working. You will not be able to edit, unless it is Checked out.
b.	CheckInAll: Enables you to CheckIn all the checked-out records of an activity. When you have multiple records checked out in an activity, to check in all the records, select this option.
To save the changes:
1.	In the Modeler, right-click on the Activity, under All Checked out Objects tab at the bottom-left corner of the window. 
2.	Select the option CheckInAll.
--- 
Figure 8.2: To save the changes
---
> NOTE:  If you are unable to store current changes and if error is generated, then you have to contact your mentor or the support team for assistance.  

### Publish your Changes.
The changes done in a modeler with respect to an activity is local to the modeler. If changes were to be viewed using the URL on the local host then it should be published to the user database.
>NOTE:  To set up the publish path to the user database, refer to Troubleshooting and Support for more details.
+ To Publish an Enterprise
When a new Application is created, the Enterprise has to be published even before the application is published.
1.	In the Enterprise Explorer window, right-click on the Enterprise (AppPoint). 
2.	Select and click Publish.
+ To Publish Application/Application Category
1.	Right-click on the Application Category HRIS, and select Publish.
--- 
 Figure 7.1: Publishing Application Category
---
+ To Publish your Activity:
1.	Select the All CheckedOut Objects option displayed at the bottom of the screen. This displays the activity name and the corresponding activity owner.
2.	Right-click on the<Activity name>, select Publish option from the available list. 
3.	Login to the UI to see the changes you have made in the activity. 
 
### Close the Modeler
To close and exit from the Modeler:
1.	In the BizAPP Enterprise window, Click File>>Exit. OR
2.	Scroll to the top right corner and click Close button. A pop-up message appears on screen to confirm whether you want to close the modeler.
3.	Click Ok. The Modeler is closed.
>NOTE:  If you have not saved your changes before closing the Modeler then a pop-up window appears on screen to confirm whether you want to CheckIn all your changes. Select CheckIn. 

#### Connect to an Existing Model
Once you have started work on a new activity, you can connect to an existing solution model and continue to work on the ongoing activity
To work on to an existing solution model:
1.	Double-click on the BizAPP Studio Modeler icon. 
2.	In the BizAPP Studio Modeler window, select the “Connect to an existing model” option, and click Next.
 
3.	In the Download existing or create a new solution model section, click on the drop-down of **Select an empty repository to create solution model** and choose the local repo that is listed. 
4.	Click **Finish**. The **BizAPP Studio-Client** window appears on screen. 
5.	Login with your credentials. Refer to: Login to BizAPP Studio-Client for more details.
 
Now, the **Activity Manager** window is available on screen. 

### Continue Ongoing Development Activity
You can open your ongoing activity either from the Modeler login by connecting to the existing solution model or from the Modeler landing page.
1.	In the Activity Manager window, click on the drop-down and choose a Release/Sprint where the activity would be delivered in the “Select the Release where the activity would be delivered” text box.
2.	Select an Application from the drop-down of “Which application do you want to work-on?” 
3.	To work on an existing activity, select the option “Continue ongoing development activity”. OR
4.	In the Modeler Enterprise view, select File>>Open Activity.
5.	Select the My Activities  option, click  , choose your activity from the list, and click Ok. 
6.	If you are a co-developer in another activity, select the Other Activities section, and choose an activity you want to co-work.
7.	Click Open. The selected activity will get loaded on to your system. 
The Modeler is available for you to continue with application development.

### Submit Activity for Review
After an activity is validated or tested, you can submit it for review. The status of the activity changes to Pending Review state. You cannot work on the activity which is in the pending review state. 
To submit an activity for review, do the following:
1. Select **All CheckedOut Objects** option displayed at the bottom of the screen. This displays the <activity name>and the corresponding activity owner.
2. Right-click on the **<activity name>** and select the **Submit for Review** option.
---
Figure 9.1: Submit Activity for Review_
---
3. In the Comment editor, enter a comment text. 
4. In the Impact Analysis editor window, enter the impact of the change if any. Otherwise, enter “no impact”.
--- 
Figure 9.2: Submit an Activity for Review
---
5. Click **OK**.
Now, the activity has been submitted for review. It is in the pending review state until the Manager approves it.
>NOTE: You can only work on the activities which are in the “Work in Progress” state. 

### Approving an Activity 
An activity that is submitted for review can be either approved or rejected by your mentor. After an activity is approved, you cannot make any changes to that activity. When an activity is rejected, you can rework on that activity to get it approved. A rejected activity goes through the same workflow as a new activity. 
>NOTE: Only user with User Management responsibility can approve, reject and publish an activity. 
To approve an Activity:
1. Select **All CheckedOut Objects** option displayed at the bottom of the screen. This displays the <Activity_name> and the corresponding Activity Owner.
2. Right-click on the **<activity_name>** with status *Submitted*, and select **Approve** to approve the activity.
---
Figure 14: Approval Process
---
3. The status of the activity changes as **Approved**. 
4. Otherwise, right-click on **<activity_name>** with status *Submitted for Review* and select **Reject**. 

The status of the activity changes as “Assigned for Rework”. 

### Rework on your Activity
The rejected activity or Activity assigned for rework goes through the same workflow as a new activity. You can rework on the activity, submit for review and get it approved. 
1.	Select the **All CheckedOut Objects** option displayed at the bottom of the screen. This displays the **<Activity name>** and the corresponding **<Activity Owner>**.
2.	Right-click on the **<Activity name>** and select the **WorkOn** option.
3.	Make the necessary changes, and click **Save and SubmitForReview**. 

Now, **Approve** and **Reject** options are available for approver to approve or reject the activity. Follow the instructions as mentioned in Approving an Activity. 




