# Overview
This Plan ensures a smooth customer transition for searching, viewing and buying the loved jewelry based on the size. Can email the store jeweler for custom designing with a description.

# Software Requirements
The Heard Jewelry Store Web Application will help in browsing items, adding to cart, searching for required jewlery and proceed with the purchase. This website is built using Power Apps, SharePoint document libraries, and Power Automate, the app will feature role-based user access, a smooth image slider, selecting size and quanties of jewlery with real-time email for customer-owner interactions. Images will be uploaded and stored to SharePoint Document Library, ensuring seamless storage and retrieval, while workflows will manage speed backend operations. The project is good with performance, security, and scalability, delivering latest, flexible experience for users and enhancing the store’s online presence.

## Functional Requirements
### login/signup

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 | The system SHALL allow users to log in to the application using their credentials.|
| FR2 | The system SHALL provide a signup option for new users.|
| FR3 | The system SHALL allow users to enter details such as name,phone number, and email during the signup process.|
| FR4 | The System SHALL allow user to save their information.|
| FR5 | The system shall show a error message, such as "Invalid username or password,".|


### Input Ingredients

| ID  | Requirement |
| :-------------: | :----------: |
| FR6 | The system SHALL allow users to input a list of ingredients they have or wish to use for cooking.|
| FR7 | The system SHALL validate and process user-inputted ingredients for accurate and relevant recipe recommendations.|
| FR8 | The system SHALL suggest ingredient substitutions based on user choice.|
| FR9 | The system SHALL enable users to edit and modify their ingredient preferences.|
| FR10| The system shall smartly recommend extra ingredients, using user input to improve the variety and completeness of recipes.|

### Recommend Recipes

| ID  | Requirement |
| :-------------: | :----------: |
| FR11 | The system SHALL recommend recipes based on user-inputted ingredients and preferences.|
| FR12 | The system SHALL provide personalized recipe suggestions based on user rating and reviews.|
| FR13 | The system SHALL allow users to filter and sort recipe recommendations based on various criteria. |
| FR14 | The system SHALL continuously update and add new recipes to the recommendation database.|
| FR15 | The system SHALL include a feature that encourages users to explore recipes from different cuisines.|

### view Recipe

| ID | Requirement |
| :-------------: | :----------: |
| FR16 | The system SHALL allow users to search for recipes based on ingredients.|
| FR17 | The system SHALL allow users to view detailed information about a specific recipe.|
| FR18 | The system shall allow the user to save and print the recipe.|
| FR19 | The system SHALL provide an option for users to view the instructions and other details of a recipe.|
| FR20 | The system SHALL display the source or origin of each recipe, providing information about where the recipe was sourced.|

### Save&Print Recipe

| ID | Requirement |
| :-------------: | :----------: |
| FR21 | The system SHALL allow users to save their favorite recipes for quick access.|
| FR22 | The system SHALL provide a printing option for users to print out recipes for offline reference.|
| FR23 | Users SHALL have the capability to create a personalized recipe collection for future use.|
| FR24 | The system SHALL generate print-friendly recipe layouts, ensuring clear and concise printing.|
| FR25 | Users SHALL be able to organize and categorize saved recipes based on personal preferences or occasions.|


### Feedback

| ID  | Requirement |
| :-------------: | :----------: |
| FR26 | The system SHALL allow users to provide feedback on recipes, including comments.|
| FR27 | The system SHALL display average ratings for each recipe based on user feedback.|
| FR28 | The system SHALL enable users to edit or delete their feedback.|
| FR29| The system SHALL store user feedback information for analysis and improvement.|
| FR30 | The system SHALL incorporate a feature allowing users to mark recipes as favorites, providing a convenient way to keep track of preferred dishes for future reference.|

## Non Functional requirements

### Performance and Scalability

| ID  | Requirement |
| :-------------: | :----------: |
| NFR31| The system shall handle up to 1,000 users traffic without noticeable lag.|
| NFR32| Page load times, including images and description with price shall not exceed 3 seconds under less traffic conditions.|
| NFR33| Backend workflows, such as image and details loading and ma processes, shall complete within 2 seconds.|
| NFR34|The platform shall dynamically scale to handle traffic when peak usage periods, such as sales events.|  
| NFR35|The system shall support large product catalogues with thousands of jewellery product entries without requiring reconfiguration.|

### Security and Data Protection

| ID  | Requirement |
| :-------------: | :----------: |
| NFR36| Sensitive data, such as chat histories and user credentials, shall be private in their own email account. |
| NFR37| Multi-factor authentication (MFA) shall be enabled for important accounts like admin accounts to enhance security.|
| NFR38|Login attempts shall be limited to prevent brute-force attacks, protecting user accounts.|
| NFR39|The system shall log all user and admin activities for audit and compliance purposes.|
| NFR40|All communications between the system and users shall be encrypted using HTTPS protocols.|

### Responsiveness and Compatibility

| ID  | Requirement |
| :-------------: | :----------: |
| NFR41| The application shall be fully interactive, ensuring seamless usage across desktops, tablets, and smartphones. |
| NFR42| Compatibility shall be maintained with the latest versions of Chrome, Edge, Firefox, and Safari.|
| NFR43|The user interface (UI) shall dynamically adapt to different screen sizes and devices.|
| NFR44|Touch screen shall be supported on mobile devices to enhance usability. |
| NFR45|Accessibility standards, such as WCAG 2.1 compliance, and leave a comment to jeweller shall be implemented to support users with disabilities.|


### Maintainability and Modularity

| ID  | Requirement |
| :-------------: | :----------: |
| NFR46| All workflows in Power Automate shall use reusable templates to simplify updates and maintenance. |
| NFR47| SharePoint lists shall include versioning to track changes and allow rollback if necessary. |
| NFR48|Documentation shall provide clear instructions for setup, operation, and troubleshooting.|
| NFR49|The system shall support incremental updates without affecting existing functionalities. |
| NFR50|Error messages shall include diagnostic codes to help developers quickly identify and fix issues.|

### Data Backup and Integrity

| ID  | Requirement |
| :-------------: | :----------: |
| NFR51| Daily backups shall cover all SharePoint lists, Power Automate workflows, and user data. |
| NFR52| Backup failures shall trigger immediate alerts to the admin team for resolution.|
| NFR53| Historical data, including user and order records, shall be retained for up to 3 years.|
| NFR54| Weekly integrity checks shall verify the consistency of the database and prevent errors.|
| NFR55| An automated recovery mechanism shall ensure data restoration within 1 hour of a system failure. |


# Change management plan


## How will you train people to use it?
To ensure a smooth transition and user adoption, a comprehensive training program will be implemented. Initially, an online training session will be conducted for all users, providing step-by-step guidance on navigating the platform, searching for recipes, and utilizing personalized features. Additionally, multi-modal training resources including documentation, videos, live sessions, and in-app chatbots to guide users.

## How will you ensure it integrates within their ecosystem / software?
Our recipe app offers an intuitive interface for easy onboarding. By validating core features like login work, we ensure key requirements are fulfilled. Flexible APIs facilitate data flows between the frontend and backend recommendation systems seamlessly. Cross-platform responsive design allows versatility across devices, thoroughly compatibility tested. Regular feedback refinement improve overall user experience, identifying any outstanding feasibility issues quickly so we can embed this app consistently across existing ecosystems

## How will you ensure that it any discovered issues are resolved?
An efficient issue resolution process will be implemented to address any identified concerns promptly. Users will have access to a dedicated support portal where they can report issues and receive timely updates on the resolution progress. A tiered support system will be established, with a team of technical experts available to tackle complex issues. Regular system audits and automated monitoring tools will be in place to proactively identify and resolve potential issues before users encounter them. Feedback from users will be actively sought and used to drive continuous improvement, ensuring a robust and reliable food recipe recommendation platform.

# Traceability links
This section shows how the requirements are related to other project artifacts, such as class diagrams, use case diagrams, and activity diagrams, as well as how they relate to artifacts, such as class diagrams.
 

## Use Case Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| UseCase1 | [login / signup](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR1-FR5 |
| UseCase2 | [Input Ingredients]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR6-FR10 |
| UseCase3 | [Recommend recipes](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR11-FR15 |
| UseCase4 | [View Recipe](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf )| FR16-FR20 |
| UseCase5 | [Save Recipe](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR21-FR25 |
| UseCase5 | [Print Recipe](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR21-FR25 |
| UseCase6 | [Leave Comments](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)| FR26-FR30 |


## Activity Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | [login/signup/User Information](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)| FR1-FR5, NFR36, NFR38, NFR39, NFR45, NFR46 , NFR48 |
| 2 | [Give Ingredients]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)| FR6-FR10, NFR48, NFR49 |
| 3 | [Recommend Recipes]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png )| FR11,FR12,FR14,FR15,NFR31,NFR33,NFR41,NFR47,NFR50 |
| 4 | [View Recipes]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png )| FR16-19 NFR41, NFR43, NFR44,NFR45 |
| 5 | [Filter Recipes](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png )| TBD |
| 6 | [Save & Print Recipes](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png) | FR18, FR21-25,NFR43,NFR44,NFR45 |
| 7 | [Feedback](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)| FR26-30,NFR33,NFR37,NFR38,NFR45,NFR46,NFR47 |


## Class Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | [login / signup/User](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/class%20diagram-drawio.png)| FR1-5, NFR36, NFR38, NFR39, NFR45, NFR46 , NFR48|
| 2 | [Preferred ingredients](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/class%20diagram-drawio.png)|FR6-FR10, NFR48, NFR49 |
| 3 | [Filtering engine](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/class%20diagram-drawio.png)| FR13,NFR36, NFR37 |
| 4 | [Recipe Recommendation](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/class%20diagram-drawio.png)| FR11,FR12,FR14,FR15,NFR31,NFR32,NFR41,NFR47,NFR50 |
| 5 | [View recipe](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/class%20diagram-drawio.png)| FR16-19, NFR36, NFR38, NFR39,NF42 |
| 6 | [Feedback](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/class%20diagram-drawio.png)| FR26-30, NFR28,NFR32,NFR33,NFR40,NFR41,NFR42 |

## Object Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | [login / signup/User](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR1-5, NFR36, NFR38, NFR39, NFR45, NFR46 , NFR48 |
| 2 | [Preferred ingredients](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR6-FR10, NFR48, NFR49 |
| 3 | [Filtering engine]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR13,NFR36, NFR37 |
| 4 | [Recipe Recommendation](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR11,FR12,FR14,FR15,NFR31,NFR32,NFR41,NFR47,NFR50 |
| 5 | [View recipe](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR16-19, NFR36, NFR38, NFR39,NF42 |
| 6 | [Feedback](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)| FR26-30, NFR28,NFR32,NFR33,NFR40,NFR41,NFR42 |


## WIndows Navigation Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | [Create Account Form](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Navdiagram.png ) | FR1-5, NFR31, NFR33, NFR34, NFR40, NFR41 , NFR43 |
| 2 | [Select Ingredient Form](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Navdiagram.png) | FR6-FR10, NFR43, NFR44 |
| 3 | [Recipes List]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Navdiagram.png) | FR11, FR12, FR14, FR15,NFR26, NFR27, NFR36, NFR42, NFR45|

# Software Artifacts
Here we can find all related use case, activity, window navigation, class diagrams and Object diagram of our food recipe recommendation project

* [ Use case diagram ](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/UseCase.png.pdf)
* [ Activity diagram ]( https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Activity%20Diagram.drawio.png)
* [ Class diagram ](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/class%20diagram-drawio.png)
* [ Object diagram ](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/object%20diagram.jpg)
* [ Window navigations diagrams ](https://github.com/shankymurali/GVSU-CIS-641-4WIZ/blob/main/artifacts/Navdiagram.png)
