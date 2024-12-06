# Team name: Intl Studs

# Team members: 
- Chandra Sekhar Singuru
- Uday Surneni
- Raghavendra Naidu Nayanuri

# Introduction

The goal of this project is to develop an interactive web application for a jewelry store, providing a seamless user experience for browsing and uploading images. The website will be used to showcase the store's collection through image galleries that allow users to view products of high quality. The project aims to focus on a smooth image slider for featured products.

Users will begin by either registering for a new account or logging into an existing one. Once logged in, users can view the uploaded images of jewelry pieces to the store's collection. These uploaded images will be retrieved from the database and displayed on the homepage in a slider format, providing an engaging and interactive way to explore products. This sliding feature will offer smooth transitions between images, ensuring an elegant user experience while browsing through various items.

The project will use modern web technologies like React for the front end and Node.js for the back end. Security will also be a key focus, with user authentication managed through JSON Web Tokens (JWT), ensuring safe and secure user sessions. It will also consist of a new feature that lets the user to chat with the owner of the jewel peices directly.

This project aims not only to provide a functional and secure platform for users to engage with the jewelry store’s offerings but also to deliver a modern user experience that enhances the store's brand online.

# Anticipated Technologies

To build this project, We will be using:

- Frontend: Power Apps Studio (drag-and-drop UI builder)
- Backend: Power Automate (workflows) 
- Database: SharePoint (for data storage and management)
- Authentication: SharePoint (integrates with Microsoft 365 authentication)
- File Uploads: SharePoint Document Library (for file storage)
- Version Control: Power Apps (native version control for app management)

# Method/Approach

- Environment Set-up: Set up Power Apps studio with a trial version to create the website interface. Establishing the connection between SharePoint to manage data    storage.
  For the backend using power automation to handle workflows for adding and updating data to SharePoint.
- UI/UX: Gather information from the client, collect icons for each website page, and implement them on the front end.
  Using power apps drag and drop components to design pages with templates, icons, and images per the client's requirements.
- User Authentication: Implement Microsoft authentication feature via SharePoint for secure user login.
  Configuring access level to admin, store manager, and customers for secure access to the website.
- Image Upload and Storage: By using Power Apps native controls to upload images to the SharePoint document library with ULRs and image display descriptions.
  Using dynamic gallery feature using power apps to give a smooth user experience.
- Image Display: Fetch the images from the SharePoint document library and display them dynamically on the homepage. Implement a sliding gallery feature for an       enhanced user experience.
- Testing and Deployment: Test the app for performance, security, and usability, and deploy.
- Certificate: Use the power apps interaction feature to publish the website using the upgraded plan 

# Estimated Timeline

- Week 1-2: Gathering requirements, analyzing the feasibility, and building a test website by learning the technology. 
- Week 3: Setting up the dev environment, and implementing basic authentication (register and login) using React, Node.js, and MongoDB.
- Week 4: Implement image upload functionality, store images in MongoDB, and ensure proper validation.
- Week 5: Build the dynamic image carousel and integrate the uploaded images with the front end.
- Week 6: Perform testing, resolve bugs, and prepare for deployment.
- Week 7: Final adjustments, deployment, and project documentation.
- Week 8: Final week

# Anticipated Problems

- User Management: Efficiently allowing owner access to admins and view access to the buyers. 
- Image Handling: Might be tough to handle large image files which may cause performance issues. Requires, images to be compressed or use other storage techniques before storage.
- Authentication & Security: Ensuring JWT tokens are securely handled and encrypting user data such as passwords.
- Database Storage: Storing images in MongoDB to avoid storage and retrieval delays.
