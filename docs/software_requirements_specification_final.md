# Overview
This Plan ensures a smooth customer transition for searching, viewing and buying the loved jewelry based on the size. Can email the store jeweler for custom designing with a description.

# Software Requirements
The Heard Jewelry Store Web Application will help in browsing items, adding to cart, searching for required jewlery and proceed with the purchase. This website is built using Power Apps, SharePoint document libraries, and Power Automate, the app will feature role-based user access, a smooth image slider, selecting size and quanties of jewlery with real-time email for customer-owner interactions. Images will be uploaded and stored to SharePoint Document Library, ensuring seamless storage and retrieval, while workflows will manage speed backend operations. The project is good with performance, security, and scalability, delivering latest, flexible experience for users and enhancing the store’s online presence.

## Functional Requirements
### User-Admin Communication

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 | The system shall provide a email interface for users to communicate directly with store admins.  |
| FR2 | Chat queries shall be stored in a Email inbox for future reference and response.|
| FR3 | Users shall able to upload attachments like images or documents to email queries. |
| FR4 | Users shall view their privies queries and admin replies in a mail chain history.|
| FR5 | Admins shall receive notifications for new chat queries to ensure timely responses.|

### Product Management

| ID  | Requirement |
| :-------------: | :----------: |
| FR6 | Admins shall upload and update product details, product images, product description, price, and category using Power Apps. |
| FR7 | Each product shall support multiple image uploads to a single product, with one designated as the primary image and rest of the images will slide. |
| FR8 | Products shall be categorized into predefined jewellery types like necklaces, bracelets, rings. These categories will have drop down options.|
| FR9 | Admins shall have the ability to add and remove product offers for specific seasons or events.  |
| FR10 | Admins shall add discounts or promotional coupons to desired products. |

### Image Display and Slider 

| ID | Requirement |
| :-------------: | :----------: |
| FR11 | The homepage shall feature all the dynamic image with description showcasing the latest or featured products.|
| FR12 | Users shall control the slide bar using swipe gestures on mobile and scroll arrows on desktop.  |
| FR13 | Images shall load dynamically from SharePoint database library with optimized performance to ensure a smooth loading experience.  |
| FR14 | Each product image in the slider shall include product name, size, number of quantities and price.  |
| FR15 | The slider shall include a category bar to indicate the current slide position|

### Jewelry Search and Filtering    

| ID | Requirement |
| :-------------: | :----------: |
| FR16 | Users shall search for products by type, name or keyword using a Power Apps search box feature. |
| FR17 | Recently viewed products shall appear on top of the section for user convenience.  |
| FR18 | Search results shall display only items matches are found by keywords, description.  |
| FR19 | Users shall add products to cart and come back to home page to continue shopping.|
| FR20 | The system shall allow users to combine multiple keywords to filters for advanced searches. |


### User Profile Management    
| ID  | Requirement |
| :-------------: | :----------: |
| FR21 | Users shall update their account, including name, email, and address with a Power Apps form.|
| FR22 | Users shall view their order history, in their account including product details and quantity of purchase.|
| FR23 | Admins shall add internal notes to user profiles in email for better customer management.|
| FR24 | Users shall manage their notification preferences like promotions and email notifications.|
| FR25 | A dashboard shall display personalized logs of their purchase history.|

## Non Functional requirements

### Performance and Scalability

| ID  | Requirement |
| :-------------: | :----------: |
| NFR26| The system shall handle multiple users traffic without noticeable lag.|
| NFR27| Page load times, including images and description with price shall not exceed 3 seconds under less traffic conditions.|
| NFR28| Backend workflows, such as image and details loading and ma processes, shall complete within 2 seconds.|
| NFR29| The platform shall dynamically scale to handle traffic when peak usage periods, such as sales events.|  
| NFR30| The system shall support large product catalogues with thousands of jewellery product entries without requiring reconfiguration.|

### Security and Data Protection

| ID  | Requirement |
| :-------------: | :----------: |
| NFR31| Sensitive data, such as chat histories and user credentials, shall be private in their own email account. |
| NFR32| Multi-factor authentication (MFA) shall be enabled for important accounts like admin accounts to enhance security.|
| NFR33| Login attempts shall be limited to prevent brute-force attacks, protecting user accounts.|
| NFR34| The system shall log all user and admin activities for audit and compliance purposes.|
| NFR35| All communications between the system and users shall be encrypted using HTTPS protocols.|

### Responsiveness and Compatibility

| ID  | Requirement |
| :-------------: | :----------: |
| NFR36| The application shall be fully interactive, ensuring seamless usage across desktops, tablets, and smartphones. |
| NFR37| Compatibility shall be maintained with the latest versions of Chrome, Edge, Firefox, and Safari.|
| NFR38| The user interface (UI) shall dynamically adapt to different screen sizes and devices.|
| NFR39| Touch screen shall be supported on mobile devices to enhance usability. |
| NFR40| Accessibility standards, such as WCAG 2.1 compliance, and leave a comment to jeweller shall be implemented to support users with disabilities.|


### Maintainability and Modularity

| ID  | Requirement |
| :-------------: | :----------: |
| NFR41| All workflows in Power Automate shall use reusable templates to simplify updates and maintenance. |
| NFR42| SharePoint lists shall include versioning to track changes and allow rollback if necessary. |
| NFR43| Documentation shall provide clear instructions for setup, operation, and troubleshooting.|
| NFR44| The system shall support incremental updates without affecting existing functionalities. |
| NFR45| Error messages shall include diagnostic codes to help developers quickly identify and fix issues.|

### Data Backup and Integrity

| ID  | Requirement |
| :-------------: | :----------: |
| NFR46| Daily backups shall cover all SharePoint lists, Power Automate workflows, and user data. |
| NFR47| Backup failures shall trigger immediate alerts to the admin team for resolution.|
| NFR48| Historical data, including user and order records, shall be retained for up to 3 years.|
| NFR49| Weekly integrity checks shall verify the consistency of the database and prevent errors.|
| NFR50| An automated recovery mechanism shall ensure data restoration within 1 hour of a system failure. |


# Change management plan


## How will you train people to use it?
Objective:
This website has categories of jewelry like rings, necklace, bracelets from which user can filter what they want to purchase. Customers will have a search bar which effectively filters jewelry based on the description of the products. When a user is making a purchase, it should ask for Name and address before taking to payments page.

Training Methods:
By giving hands on workshop will be conducted for managers to use and update the website features. Step by step process will be given from the login page to add and update product images, update prices and reply to customers who are contacting over the email for custom jewelry with reference images. Separate documentation files will be created for each step and stored in a shared location by managing the access level. Admin and Managers can email one of our team members if there are any issues that need to be fixed on the website or having trouble using any functionalities. 

## How will you ensure it integrates within their ecosystem / software?
Objective: Present technologies are powerful and compatible to many versions. Using the latest technologies like power apps with minimum code and increase the performance, maintenance and feasible for page navigating and secure. 
1. Environment Compatibility Testing:
Since Power Apps is web-based we tested by logging from different browsers and devices. All the functionals are working fine in all the platforms. Verified compatibility in different operating systems like windows, Linux, macOS PowerApps are working fine without additional configuration. By Conducted comprehensive testing in PowerApps environment to replicate real-world functions across various configurations.
2. Data Synchronization:
SharePoint Integration: There is real time data access between PowerApps and SharePoint. Any updates made in SharePoint will be automatically reflected in apps. Product data, images, and other information will be automated between power apps and front-end using power automation. So, the data will be up-to-date. By setting up dynamic data fetching in power apps will automatically retrieve and update data in frontend from SharePoint. We implement scheduled updates within the power app automation to sync data periodically to maintain the backups and inventory or product details reflected in the application.
3.Define user Access:
In SharePoint roles will be created as admin, store manager and customer. By defining the permissions for each role like granting full access to admin. Limited access to edit the quantity or price of the products by store manager. Browsing and buying products for customers. We can implement Microsoft 365 authentication to handle user login and verification for admin account since it’s had more privileges and Users are granted with appropriate role-based access in the apps. Role baes access in PowerApps can be granted to certain pages, actions and functionalities on user roles. Only store managers should have access to update and management features. SharePoint permissions parallel to PowerApps, ensures only user’s specific roles can access or edit SharePoint data.


## How will you ensure that it any discovered issues are resolved?
We will be monitoring and identifying the issue or bugs by testing, user feedback, and analytics tools. After finding the issues they shell be prioritized based on the severity and impact on business and security. Once we developers got notified about the issue immediate action will be taken to resolve the issue in PowerApps platform. After the fix Client will be notified and monitoring will be done for a week after fixing the issue. If the issue was not able to fix of effecting the business changes will be reverted to previous backup update. Documentation will be done for the issue resolution steps taken for future reference. 

# Traceability links
This section shows how the requirements are related to other project artifacts, such as class diagrams, use case diagrams, and activity diagrams, as well as how they relate to artifacts.
 
## Use Case Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| UseCase1 | [Login / Signup](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR1-FR5, NFR31-NFR33 |
| UseCase2 | [Manage Products]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR6-FR10, NFR41-NFR42 |
| UseCase3 | [View and Browse Jewelry](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR11-FR15, NFR26-NFR30 |
| UseCase4 | [Search and Filter Products](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf )| FR16-FR20, NFR36-NFR40 |
| UseCase5 | [Manage User Profiles](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR21-FR25, NFR43-NFR45 |
| UseCase6 | [Handle Communication (Email/Chat)](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR1-FR5, NFR34-NFR35 |
| UseCase7 | [Secure and Backup Data](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| NFR46-NFR50 |
| UseCase8 | [Responsive and Accessible Design](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| NFR36-NFR40 |
| UseCase9 | [System Performance and Scaling](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| NFR26-NFR30
 |


## Activity Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| Act1| [User Registration/Login](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)| FR1, FR21, NFR31-NFR33 |
| Act2 | [Product Upload and Management]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)| FR6-FR10, NFR41-NFR42 |
| Act3 | [Image Display on Homepage]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png )| FR11-FR15, NFR26-NFR30 |
| Act4 | [Product Search and Filtering]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png )| FR16-FR20, NFR36-NFR385 |
| Act5 | [User Profile Updates](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png )| FR21-FR25, NFR43-NFR45 |
| Act6 | [Real-time Communication](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png) | FR1-FR5, NFR34-NFR35 |
| Act7 | [Data Backup and Recovery](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)| NFR46-NFR50 |
| Act8 | [Performance Optimization](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)| NFR26-NFR30 |
| Act9 | [Accessibility and Responsiveness](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)| NFR36-NFR40 |


## Object Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| Obj1 | [User Object](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR1-FR5, FR21-FR25, NFR31-NFR33 |
| Obj2 | [Admin Object](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR6-FR10, NFR34, NFR41-NFR42 |
| Obj3 | [Product Object]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR6-FR10, FR11-FR15, NFR41-NFR42 |
| Obj4 | [Image Object](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR11-FR15, NFR26-NFR30 |
| Obj5 | [Search Object](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR16-FR20, NFR36-NFR40 |
| Obj6 | [Order Object](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR21-FR25, NFR43 |
| Obj7 | [Communication Object (Email/Chat)](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR1-FR5, NFR34-NFR35 |
| Obj8 | [Backup Object](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| NFR46-NFR50 |
| Obj9 | [UI Object](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FFR11-FR15, FR16-FR20, NFR36-NFR40 |
| Obj10 | [System Object](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| NFR26-NFR30, NFR46-NFR50 |


# Software Artifacts
Find all related use case, activity diagram, window navigation diagram,CRC diagram, class diagrams and Object diagram of our Hard Jewelry project.

* [ Use case Admin ](https://github.com/Chandra953/GVSU641-IntlStuds/blob/main/artifacts/UseCase_Admin.jpg)
* [ Use case User ](https://github.com/Chandra953/GVSU641-IntlStuds/blob/main/artifacts/UseCase_User.jpg)
* [ Activity diagram Admin ](https://github.com/Chandra953/GVSU641-IntlStuds/blob/main/artifacts/ActivityDiagram_Admin.jpg)
* [ Activity diagram User ](https://github.com/Chandra953/GVSU641-IntlStuds/blob/main/artifacts/ActivityDiagram_User.jpg)
* [ CRC_Diagram ](https://github.com/Chandra953/GVSU641-IntlStuds/blob/main/artifacts/CRC_Diagram.jpg)
* [ Class diagram ](https://github.com/Chandra953/GVSU641-IntlStuds/blob/main/artifacts/Class_Diagram.jpg)
* [ Object diagram ](https://github.com/Chandra953/GVSU641-IntlStuds/blob/main/artifacts/Object_Diagram.jpg)
* [ Window navigations diagrams ](https://github.com/Chandra953/GVSU641-IntlStuds/blob/main/artifacts/Windows_Nav_Diagram.jpg)
