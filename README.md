# Welcome to our Repository, this is the Final Project for EE368 #

## Overall Features: ## 
- Feature 1 Password Bug
- Feature 2 Landing Page
- Feature 3 Reports Optimization
- Feature 4 More Report Charts


### Team Members

| Name          | Email                    | Role    |
|---------------|--------------------------|---------|
| Aidan Collins | aitcolli@clarkson.edu    | Leader  |
| Robert Arcate | arcater@clarkson.edu     | Member  |
| Nick Engle    | englena@clarkson.edu     | Member  |
| Brandon Hacic | hacicbt@clarkson.edu     | Member  |
| Zak Konik     | konikza@clarkson.edu     | Member  |
| Aydan O'Brien | obriena@clarkson.edu     | Member  |

Test Results can be found in this document:
https://docs.google.com/document/d/11hkKJfId4TcZ7m1AtkmPOLXiFLUp8G-kRpQRlxyWKQ0/edit

------------------------------------------------------------------------------------------------------------------------------------


## mangoSource Patch Notes 

Release Date: April 20, 2024


### New Features

1. **Landing Page Revamp**
   - **Current Behavior:** Previously, if a user’s home page setting was not configured, they were directed to the watch list page by default. This page could be set or unset using buttons on the right side of the navigation bar.
   - **New Improvements:**
     - **Default Landing Page:** Now, all users will see a new default landing page upon login, which provides a welcoming and informative dashboard. This page includes essential information about mangoSource, details on the sensors being used, and integrates a watch list interface.
     - **Navigation Icon:** An icon for the new landing page has been added to the navigation bar, making it easily accessible from anywhere in the application. This icon ensures that users can quickly return to the main dashboard at any time.
   - These changes aim to enhance user orientation and provide immediate access to important data and functionality upon login.

### Enhancements

1. **Reports Optimization**
   - **Current Behavior:** Generating a report for a set of sensors over a specified time range could be slow due to database queries.
   - **New Improvements:**
     - The database architecture has been optimized, significantly speeding up the report generation process. This results in faster access to needed data and more efficient analysis.

### Bug Fixes

1. **Password Bug Fix**
   - **Current Behavior:** Attempting to change an administrator’s password resulted in an error and the change would not be applied.
   - **Resolved Issue:** This issue has been fixed. Administrators can now update passwords without encountering any errors, ensuring secure and uninterrupted access to the platform.
2. **Build Properties**
   - **Current Behavior:** Project not compiling due to improper build properties file path
   - **Resolved Issue:** This issue has been fixed. Need to update the file path for tomcat.home and db.url depending on where your mangosource file path and tomcat file path are.
3. **SRC_GEN**
   - **Current Behavior:** Project not compiling due to missing src_gen error.
   - **Resolved Issue:** This issue has been fixed. Users need to manually add src_gen file into mangosource folder and rrerun ant fullDeploy.
### How to Update
- **Step 1**: git clone the repo 
- **Step 2** Copy mangosource file into the mango folder
- **Step 3** Fix Build properties and SRC_gen 
- **Step4** Open the terminal and CD into mangoSource folder and run command: ant fullDeploy
**Step5** Enjoy Mango



------------------------------------------------------------------------------------------------------------------------------------

