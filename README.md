# Facial Investigator

Facial Investigator is an investigation app that can be used by the officials of an investigation agency.Criminal records of a suspected person can be fetched if existing by recognizing the facial descriptors.Information and photograph of new wanted persons can be added to database. Details of a rescued missing person can be fetched if found in records by analyzing facial features.More cases of missing people can be registered.Only authorized users can access the app through their face ID.Users can also edit their profile images.

# Preview
![tech33nology ppt template - 10 slides - creative (1) pptx](https://user-images.githubusercontent.com/92640652/170768345-70c77fdc-4a26-4d54-a6a8-523c1d1ec3d2.png)

![tech33nology ppt template - 10 slides - creative (1) pptx](https://user-images.githubusercontent.com/92640652/170854655-b2442e77-74fc-4aae-9af5-3c463d555ec9.png)

![tech33nology ppt template - 10 slides - creative (1) pptx](https://user-images.githubusercontent.com/92640652/170854805-43c881d6-1918-4709-ba16-2b13e5f8afb9.png)


## Table of content
  - [Features](#features)
  - [TechStack](#techstack)
  - [Development](#development)
## Features
- **Fetches information about suspected criminal**
  - Captures a snap of the suspected person's face and checks if any criminal record of the person exists and displays all the details. 
- **Add new criminal records**
  - Details like name,crime,regional police,since when is the person wanted and photograph of new criminal people can be entered in the database.
  - Informs the user if no face was detected and to add a clear image
- **Displays the details of a rescued person**
  - Takes a pic of the reported person to be rescued and checks if any information of the person exists and displays all the details.
- **Upload new data to database of missing people**
  - Enter details like name,contact,address of new people who went missing in the database.
  - Informs if the uploaded image is not in valid format and to upload again.
- **Authentication using face id and password**
  - New users must sign up using email,password and face ID.
  - Informs if an image without any face was used for SignUp.
  - Existing users may log in with email and faceID.
- **User can view/update profile**
  - Details of the logged in user are displayed.
  - Option to edit the image of the user.
- **Sessions created for login**
  - The user who has logged in is remembered by creating sessions.
  - A non logged in user cannot access the authorized pages by typing their url.
- **Passwords are stored securely in hashed form using bcrypt**
- **Responsive Website,can be easily used in mobile devices.**

![technology ppt template - 10 slides - creative (1) pptx](https://user-images.githubusercontent.com/92640652/170773666-2af3d9c2-89bb-4201-9250-b88db7039d3b.png)

 ![technology ppt template - 10 slides - creative (1) pptx](https://user-images.githubusercontent.com/92640652/170773848-f492e8e7-32e1-4105-af34-2d1b1fcb0cb9.png)


## TechStack
![technology ppt template - 10 slides - creative (1) pptx](https://user-images.githubusercontent.com/92640652/170002150-3d0c4fa0-4517-4681-8586-06f9bdb31595.png)

1. Front End/Client Side
   - ReactJS
   
2. BackEnd Server:
    - Express NodeJS
    - face-api.js built over TensorFlowJS - Facial Detection
    - Heroku NodeJs environment - deployment.
    - Multer - Save images in server temporarily for identification.
    - Sharp - Conversion image to jpeg format

3. Data Management (Database): 
    - MongoDB - Data management and hosting
    - Cloudinary - Storing images in form of url.
    
## Development
### Setup
1. Run `npm install` in the root directory to install all necessary dependencies.
2. Run `cd client` and again, run `npm install` to install dependencies for client side.
3. Move `C:\facial-investigator\node_modules\@tensorflow\tfjs-node\deps\lib\tensorflow.dll` to `C:\facial-investigator\node_modules\@tensorflow\tfjs-node\lib\napi-v5\`
## Running on localhost
1. In the root directory, run `nodemon .\server.js` to start the backend server.
2. Run `cd client` and then run `npm start` to start the react app server.



