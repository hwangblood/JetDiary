<h1 align="center">MongoDB Setup</h1>

# Introducing with MongoDB

~~NoSQL databases don't store relationship data,~~ they store it differently than a relational database do.

NOSQL (Not Only SQL)

MongoDB (Hu**mongo**us)

MongoDB Atlas (Database As A Service)

| SQL      | MONGO  DB  |
| -------- | ---------- |
| Database | Database   |
| Table    | Collection |
| Row      | Document   |
| Column   | Field      |

- Atlas
- MongoDB Shell
- MongoDB Compass
- MongoDB SDKs

# Introducing with Realm Sync

Realm - Fast and scalable database (Mobile, Web, Desktop, IOT)

Realm Sync - aka Device Sync & Synchronization Service

Atlas App Service



JSON schema

Automatically - with a Developer Mode

Manually - writing the JSON structured schema



Sync Modes

Flexible (Recommanded)

Partition based (old)



Queryable fields

Data access rules & roles

# MongoDB Atlas - Create a New Project

MongoDB Atlas App Services

https://www.mongodb.com/atlas/app-services

## Create a New Project

1. Create New Project in your Orgnization

2. Create a New Database (FREE, Provider, Region, Name)

3. App Services - Build your own App

   ![image-20230828165914738](./.Section-03_MongoDB-Setup.assets/image-20230828165914738.png)

4. Create App Service

   ![image-20230828170151484](./.Section-03_MongoDB-Setup.assets/image-20230828170151484.png)

5. Create Finished!

   ![image-20230828170446496](./.Section-03_MongoDB-Setup.assets/image-20230828170446496.png)

## Add Data

1. Create Database![image-20230828171226452](./.Section-03_MongoDB-Setup.assets/image-20230828171226452.png)

2. Created finished!

   ![image-20230828171334946](./.Section-03_MongoDB-Setup.assets/image-20230828171334946.png)

# Install MongoDB Compass

1. Download MongoDB Compass and install it

   https://www.mongodb.com/try/download/compass

2. After installing, Click **Connect** button to copy database connection string![image-20230828223334074](./.Section-03_MongoDB-Setup.assets/image-20230828223334074.png)

3. Create a database user

   ![image-20230828223800711](./.Section-03_MongoDB-Setup.assets/image-20230828223800711.png)

4. Choose a connection method

   ![image-20230828224402706](./.Section-03_MongoDB-Setup.assets/image-20230828224402706.png)

   Choose **Compass** method

   ![image-20230828232932824](./.Section-03_MongoDB-Setup.assets/image-20230828232932824.png)

   Copy the connection string, then open MongoDB Compass

   ![image-20230828224626360](./.Section-03_MongoDB-Setup.assets/image-20230828224626360.png)

5. Paste connection string to Compass, and connect to database

   ![image-20230828225717516](./.Section-03_MongoDB-Setup.assets/image-20230828225717516.png)

6. Connect finished!

   ![image-20230828233134222](./.Section-03_MongoDB-Setup.assets/image-20230828233134222.png)

# MongoDB Atlas - Enable Google Sign in

## GCP Project (Generate Client ID)

1. open Google Cloud Platfrom in browser, login with Google account

   ![image-20230829002254903](./.Section-03_MongoDB-Setup.assets/image-20230829002254903.png)

2. Create project

   ![image-20230829002354853](./.Section-03_MongoDB-Setup.assets/image-20230829002354853.png)

3. Credentials

   ![image-20230829003247541](./.Section-03_MongoDB-Setup.assets/image-20230829003247541.png)

   OAuth client ID

   ![image-20230829003454821](./.Section-03_MongoDB-Setup.assets/image-20230829003454821.png)

   Configure consent screen

   ![image-20230829003627505](./.Section-03_MongoDB-Setup.assets/image-20230829003627505.png)

   OAuth consent screen

   ![image-20230829003738409](./.Section-03_MongoDB-Setup.assets/image-20230829003738409.png)

   Edit application register, and click on **SAVE AND CONTINUE**

   ![image-20230829004423173](./.Section-03_MongoDB-Setup.assets/image-20230829004423173.png)

   OAuth consent screent, setup finished

   ![image-20230829004538532](./.Section-03_MongoDB-Setup.assets/image-20230829004538532.png)

   publish app

   ![image-20230829004847719](./.Section-03_MongoDB-Setup.assets/image-20230829004847719.png)

## Create OAuth client ID for Android

1. Create OAuth client ID

   ![image-20230829005044945](./.Section-03_MongoDB-Setup.assets/image-20230829005044945.png)

2. Client ID details, Click **Create** button to finish

   ![image-20230829005710128](./.Section-03_MongoDB-Setup.assets/image-20230829005710128.png)

3. Create finished

   ![image-20230829010009699](./.Section-03_MongoDB-Setup.assets/image-20230829010009699.png)

## Create OAuth client ID for Web

1. Create OAuth client ID

   ![image-20230829005044945](./.Section-03_MongoDB-Setup.assets/image-20230829005044945.png)

2. Client ID details, Click **Create** button to finish

   ![image-20230829010125850](./.Section-03_MongoDB-Setup.assets/image-20230829010125850.png)

3. Create finished

   ![image-20230829010212336](./.Section-03_MongoDB-Setup.assets/image-20230829010212336.png)

   

## Enable Google Sign in

1. Edit Google Authentication

   ![image-20230829002712091](./.Section-03_MongoDB-Setup.assets/image-20230829002712091.png)

2. Configure Google Authentication, and Click **Save Draft**

   ![image-20230829011237468](./.Section-03_MongoDB-Setup.assets/image-20230829011237468.png)

3. Draft save finished

   ![image-20230829011315495](./.Section-03_MongoDB-Setup.assets/image-20230829011315495.png)

4. review draft & deploy

   ![image-20230829110053298](./.Section-03_MongoDB-Setup.assets/image-20230829110053298.png)

5. check draft, and deploy

   ![image-20230829110245041](./.Section-03_MongoDB-Setup.assets/image-20230829110245041.png)

6. Google authentication setup successful

   ![image-20230829110624982](./.Section-03_MongoDB-Setup.assets/image-20230829110624982.png)
