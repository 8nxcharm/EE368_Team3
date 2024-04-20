# Welcome to our Repository, this is the Final Project for EE368 #

## Overall Features: ## 
- Feature 1 Password Bug
- Feature 2 Landing Page
- Feature 3 Reports Optimization
- Feature 4 More Report Charts

MEMBERS:
(leader) Aidan Collins: aitcolli@clarkson.edu 
Nick Engle: englena@clarkson.edu
Robert Arcate: arcater@clarkson.edu
Aydan O'Brien: obriena@clarkson.edu
Brandon Hacic: hacicbt@clarkson.edu
Zak Konik: konikza@clarkson.edu

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

### How to Update

- **Update:** Open terminal and CD into mangoSource folder and run command: ant fullDeploy



------------------------------------------------------------------------------------------------------------------------------------

