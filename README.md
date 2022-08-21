# Job Portal

Zephyr Job Portal is a  web app based on the MERN stack that helps optimize the  application process. Users can select their role (Applicant/Recruiter) and create an account. In this web app the login session is persistent and the REST API is secured by her JWT token validation. Once logged in, recruiters can create/delete/update jobs, shortlist/approve/reject applications, view resumes, and edit profiles. Applicants can also view jobs, perform fuzzy searches using various filters, apply for jobs using SOP, view resume, upload profile picture, upload resume, edit profile can do. It is therefore an all-in-one solution for  application systems.


## Instructions for initializing web app:

- Start MongoDB server: `sudo service mongod start`
- Move inside backend directory: `cd backend`
- Install dependencies in backend directory: `npm install`
- Start express server: `npm start`
- Backend server will start on port 4444.
- Now go inside frontend directory: `cd ..\frontend`
- Install dependencies in frontend directory: `npm install`
- Start web app's frontend server: `npm start`
- Frontend server will start on port 3000.
- Now open `http://localhost:3000/` and proceed creating jobs and applications by signing up in required categories.


