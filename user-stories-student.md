## Project overview
it is an educational system for coding boot camps. using the current lime cohort as an inspiration.
## Requirements 
### user: students
- students should be able to navigate and filter course content from a web app.
- students can track the progress of course material and exercises.
- students can give a feed back on their level of understanding on each session.
- Students can ask questions per session.
### user: admins
- admin can track students progress. and 
- update session info (instructor, level of complexity, importance, starting time)
- send notification 

## Architecture
fixable and uncoupled use of technologies following a single source of truth. for example;
- content: markdown files hosted on github (single source of truth)
- plan: google sheet (single source of truth)
- calender : google calender based on google sheet (linked to plan)
- student's data: database (single source of truth)
## Main components
### frontend:
- for admins 
- for students
### backend:    
- database
- optional integrations(slack, google calender, discord,...)
#
## User Stories : Student


### Acceptance Criteria

database 

