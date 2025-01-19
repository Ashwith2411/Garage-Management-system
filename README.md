# Garage-Management-system
Garage Management system 
The Garage Management System is a valuable tool for self-propelled repair quickness, helping them 
deliver top-notch service, increase functional efficiency, and build lasting customer relationships. 
With its user-friendly interface and powerful features, GMS empowers garages to thrive in a militant 
market while ensuring a seamless and satisfying experience for both customers and staff.
Salesforce 
intro:
Are you new to Salesforce? Not sure exactly what it is, or how to use it? Don’t know 
where you should start on your learning journey? If you’ve answered yes to any of these 
questions, then you’re in the right place. This module is for you. 
Welcome to Salesforce! Salesforce is game-changing applied science, with a host of 
productivity-boosting features that will help you sell smarter and faster. As you work 
toward your badge for this module, we’ll take you through these features and answer 
the question, “What Salesforce is anyway?”.
What Is Salesforce? 
Salesforce is your customer success platform, designed to help you sell, service, market, 
analyze, and connect with your customers. 
Salesforce has everything you need to run your business from anywhere. Using 
standard products and features, you can manage your relationship with prospects and 
customers, collaborate and engage with employees and partners, and store your data 
securely in the cloud. 
So what does that cruel? Well, before Salesforce, your contacts, emails, follow-up tasks, 
and prospective deals might have been organized something like this: 
https://youtu.be/r9EX3lGde5k
Creating Developer Account: 
Creating a developer org in salesforce. 
1. Go to https://developer.salesforce.com/signup
2. On the sign up form, enter the following details : 
1. First name & Last name 
2. Email 
3. Role : Developer 
4. Company : College Name 
5. County : India 
6. Zip code : pin code 
7. Username : should be a combining of your name and company
This need not be an actual email id, you can give anything in the format : 
username@organization.com 
Click on sign me up after filling these. 
Account Activation 
Go to the inbox of the email that you used while signing up. Click on the verify account to 
activate your account. The email may take 5-10mins.
After confirming the account, you will be redirected to this page 
Object
What Is an Object? 
Salesforce objects are database tables that permit you to store data that is specific to 
an arrangement. What are the types of Salesforce objects? 
Salesforce objects are of two types: 
1. Standard Objects: Standard objects are the kind of objects that are provided by 
salesforce.com such as users, contracts, reports, dashboards, etc. 
2. Custom Objects: Custom objects are those objects that are created by users. 
They supply data that is unique and essential to their agreement. They are the 
heart of any diligence and provide a structure for sharing data.
To Navigate to the Setup page:
Click on the gear icon? click setup.
To create an object:
1. From the setup page? Click on Object Manager? Click on Create? Click on Custom 
Object.
2. On the Custom object defining page:
3. Enter the label name, plural label name, click on Allow reports, Allow search.
4. Click on Save.
 output after saving it 
Create Customer DetailsObject 
Create Appointment Object 
Create Service records Object 
Create Billing details and feedback Object 
 
Creating a Custom Tab 
Customer Details 
Creating Remaining Tabs 
Appointments, Service records,Billing details and feedback


The Lightning App 
An app is a collection of items that work together to serve a special function. In Lightning 
Experience, Lightning apps give your users access to sets of objects, tabs, and other items 
all in one convenient bundle in the navigation bar. 
Lightning apps let you brand your apps with a custom color and logo. You can even 
include a utility bar and Lightning page tabs in your Lightning app. Members of your 
organization can work more efficiently by easily switching between apps. 
Fields 
When we talk about Salesforce, Fields represent the data stored in the columns of a 
relational database. It can also hold any valuable information that you require for a 
specific object. Hence, the overall searching, deletion, and editing of the records become 
simpler and quicker. 
Types of Fields 
1. Standard Fields 
2. Custom Fields 
Standard Fields: 
As the name suggests, the Standard Fields are the predefined fields in Salesforce that 
perform a standard task. The main point is that you can’t simply delete a Standard Field 
until it is a non-required standard field. Otherwise, users have the option to delete them 
at any point from the application freely. Moreover, we have some fields that you will find 
common in every Salesforce application. They are, 
● Created By 
● Owner 
● Last Modified
● Field Made During object Creation 
Custom Fields: 
On the other side of the coin, Custom Fields are highly flexible, and users can change 
them according to requirements. Moreover, each organizer or company can use them if 
necessary. It means you need not always include them in the records, unlike Standard 
fields. Hence, the final decision depends on the user, and he can add/remove Custom 
Fields of any given form.
Creation of fields for the Customer Details object 
 
Creation of Lookup Fields 
Creation of Checkbox Fields 
Creation of Date Field on Appointment Object :
Creation of Currency Fields 
Creation of Currency Field on Appointment Object :
Creation of Text Fields 
Creation of Text Fields in Billing details and feedback object :
Creation of Picklist Fields 
Creation of Picklist Fields in Service records object :
Creation of Picklist Fields in Billing details and feedback object :
 Creating Formula Field in Service records Object 
To create a validation rule to an Appointment 
 Object 
To create a validation rule to an Billing details and 
feedback Object 
To create a matching rule to an Customer details 
 Object 
To create a Duplicate rule to an Customer details 
 Object 
Profiles 
A profile is a group/collection of settings and permissions that define what a user can do in 
salesforce. Profile controls “Object permissions, Field permissions, User permissions, Tab 
settings, App settings, Apex class access, Visual force page access, Page layouts, Record 
Types, Login hours & Login IP ranges. You can define profiles by the user's job function. For 
example, System Administrator, Developer, Sales Representative. 
Types of profiles in salesforce 
1. Standard profiles: 
By default, Salesforce provides below-standard profiles. 
● Contract Manager
● Read Only
● Marketing User
● Solutions Manager
● Standard User
● System Administrator.
We cannot delete standard ones 
Each of these standard ones includes a default set of permissions for all of the 
standard objects available on the platform. 
2. Custom Profiles: 
Custom ones defined by us. 
They can be deleted if there are no users assigned to that particular one.


sales person Profile 
Role & Role Hierarchy 
A role in Salesforce defines a user's visibility access at the record level. Roles may be used 
to specify the types of access that people in your Salesforce organization can have to data. 
Simply put, it describes what a user could see within the Salesforce organization.
Creating Manager Role 
Creating another roles 
Users 
A user is anyone who logs in to Salesforce. Users are employees at your company, such as 
sales reps, managers, and IT specialists, who need access to the company's records. Every 
user in Salesforce has a user account. The user account identifies the user, and the user 
account settings determine what features and records the user can access.
Create User 
1. Go to setup >> type users in the quick find box >> select users >> click New user. 
2. Fill in the fields 
1. First Name : Nicklaus
2. Last Name : Mikaelson
3. Alias : Give an Alias Name
4. Email id : Give your Personal Email id
5. Username : Username should be in this form: text@text.text
6. Nick Name : Give a Nickname
7. Role : Manager
8. User license : Salesforce
9. Profiles : Manager
creating another users 
1. Repeat the steps and create another user using
1. Role : sales person
2. User license : Salesforce Platform
3. Profile : sales person 
Note : create at least three users with these permissions
Public groups 
Public groups are a valuable tool for Salesforce administrators and developers to 
streamline user management, data access, and security settings. By creating and using 
public groups effectively, you can maintain a secure and organized Salesforce 
environment while ensuring that users have appropriate access to the resources they 
need.
Creating New Public Group 
Sharing Setting 
Salesforce allows you to configure sharing settings to control how records are accessed 
and shared within your organization. These settings are crucial for maintaining data 
security and privacy. Salesforce provides a mixture of tools and mechanisms to define and 
enforce sharing rules, such as:
arrangement-Wide Default (OWD) Settings:
These settings define the default level of access for all objects within your Salesforce org.
OWD settings include Private, Public Read-Only, Public Read/Write, and Controlled by 
Parent.
OWD settings can be configured for each standard and custom object.
Role Hierarchy:
Salesforce uses a role hierarchy to determine record access.
Users at higher levels in the hierarchy have greater access to records owned by or shared 
with users lower in the hierarchy.
The role hierarchy is often used in combining with OWD settings to grant different levels 
of access.
Profiles and Permission Sets:
Profiles and permission sets allow executives to specify object-level and field-level 
permissions for users.
Profiles are typically used to grant general object and field access, while permission sets 
can be used to extend those permissions to specific users.
Sharing Rules:
Sharing rules are used to extend access to records for users who meet specific standards.
They can be used to grant read-only or read-write access to records owned by other users.
Manual Sharing:
executive and record owners can manually share specific records with other users or 
groups.
Creating Sharing settings 
Create a Flow 

Flow is created 
Create another Flow 
Flow is activated 
Apex Trigger 
Apex can be invoked by using triggers. Apex triggers enable you to perform custom actions
before or after changes to Salesforce records, such as insertions, updates, or deletions.
A trigger is Apex code that executes before or after the following types of operations:
● insert
● update
● delete
● merge
● upset
● undelete
Apex handler 
Open developer console and create new apex class name as “AmountDistributionHandler ”
and add the following code in the console
create a report folder 
Sharing a report folder 
 We gave the manager view access to the manager 
Create Report Type 
Click on save 
Create Report 



Create Dashboard Folder 
Create Dashboard

