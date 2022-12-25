# Talent Network

Talent Network is a MERN Stack based web app which helps in streamlining the flow of job application process. It allows users to select there roles (applicant/recruiter), and create an account. In this web app, login session are persistent and REST APIs are securely protected by JWT token verification. After logging in, a recruiter can create/delete/update jobs, shortlist/accept/reject applications, view resume and edit profile. And, an applicant can view jobs, perform fuzzy search with various filters, apply for jobs with an SOP, view applications, upload profile picture, upload resume and edit profile. Hence, it is an all in one solution for a job application system.
![App-1](https://user-images.githubusercontent.com/58124613/208325150-6042f5cd-95b4-4599-83f4-42e6eae9e7e3.png)

![one-1](https://user-images.githubusercontent.com/58124613/208325188-6cda7dc9-be8b-4cc7-b948-87e354da8b78.png)

![two-1](https://user-images.githubusercontent.com/58124613/208325196-fda28950-cc50-4b94-b6b0-13563388e81d.png)

![add-1](https://user-images.githubusercontent.com/58124613/208325618-1d35f671-9c45-41a3-9848-98aab5c10c0c.png)

![josh-1](https://user-images.githubusercontent.com/58124613/208326023-5483dc9a-d80b-4c3e-a1dc-4e948b2d8a19.png)

![noah-1](https://user-images.githubusercontent.com/58124613/208326034-b45a75bc-4787-4e39-ab2f-91cee73b8312.png)

![rich-1](https://user-images.githubusercontent.com/58124613/208326042-37e45c75-32f1-4e02-914f-b77bd97f45d1.png)


Directory structure of the web app is as follows:

```
- backend/
    - public/
        - profile/
        - resume/
- frontend/
- README.md
```

## Instructions for initializing web app:

- Install Node JS, MongoDB in the machine.
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

## Dependencies:

- Frontend
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
  - axios
  - material-ui-chip-input
  - react-phone-input-2
- Backend
  - bcrypt
  - body-parser
  - connect-flash
  - connect-mongo
  - cors
  - crypto
  - express
  - express-session
  - jsonwebtoken
  - mongoose
  - mongoose-type-email
  - multer
  - passport
  - passport-jwt
  - passport-local
  - uuid

# Machine Specifications

Details of the machine on which the webapp was tested:

- Operating System: Elementary OS 5.1 (Hera)
- Terminal: Bash
- Processor: Intel Core i7-8750H CPU @ 2.20 GHz 2.21 GHz
- RAM: 16 GB
