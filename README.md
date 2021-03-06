# Deployed At
https://interview-creation-portal-tss.herokuapp.com/

# Description
A simple app where admins can create interviews by selecting participants, interview start time and end time.

# Basic Requirements
- An interview creation page where the admin can create an interview by selecting participants, start time and end time. Backend should throw error with proper error message if: 
---Any of the participants is not available during the scheduled time (i.e, has another interview scheduled)
---No of participants is less than 2
- An interviews list page where admin can see all the upcoming interviews.
- An interview edit page where admin can edit the created interview with the same validations as on the creation page.
Note: No need to add a page to create Users/Participants. Create them directly in the database

# Steps to build and run this project
- Clone this repository.
- Execute npm install
- Make sure backend is running.
- Execute npm start.
- App will start running at http://localhost:3000/
