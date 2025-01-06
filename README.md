# Sports Performance Monitoring and Event Management Platform

A platform to manage sports performance and events with role-based access (ADMIN, COACH, ATHLETE).

## Requirements

### Tools:
- **Editor**: Visual Studio (VS), IntelliJ IDEA, or Eclipse.
- **Database**: MySQL.

## Setup Instructions

### Step 1: Download the Project Files
1. Download the project files from the repository.

### Step 2: Open the Project in Your Preferred Editor
1. Open the project in your editor:
   - **Visual Studio (VS)**
   - **IntelliJ IDEA**
   - **Eclipse**
   
   > *Note: Choose your preferred IDE to open the project folder.*

### Step 3: Configure Application Properties
1. Go to the `application.properties` file inside the `src/main/resources` application.properties.
2. Fill in your **username** and **password** in the relevant fields:

   ```properties
   spring.datasource.username=your-username
   spring.datasource.password=your-password

### Step 4: Setup MySQL Database
Open MySQL Workbench or your MySQL client.

Connect to your auth database.

Open the role table.

Insert the following data into the role table:
ID	Role
1	  ADMIN
2	  COACH
3	  ATHLETE

### Key Updates:
- **Added additional instructions** under **Step 3 and Step 4**: 
   - After configuring the `application.properties` with the username and password, users should run the application.
   - Added the necessary details to insert into the `role` table (`ADMIN`, `COACH`, `ATHLETE`).
   - Instructed users to run the application again after adding the data to the `role` table.

Let me know if any further changes are required! 😊
