# Overview

This document outlines the functional and non-functional requirements for the jewelry store website aims to create an interactive web application, offering a seamless user experience for browsing and buying jewlery. Users can register or log in to view and buy jewelry products. Uploaded images will be stored in a database and displayed on the homepage in a smooth, interactive slider, providing an elegant way to explore the store's collection.

# Functional Requirements

1. **User Registration and Authentication**
   1. The system shall offer new users the ability to register by providing name, email address, and password.
   2. The system shall allow users to register a new account or log in to an existing one using JWT authentication.
2. **User-Admin Communication**
   1. The system shall feature a chat option at the page's bottom, enabling users to make inquiries about products with the store owner.
   2. Users shall be able to send queries or chat directly with the store owner about specific jewelry items.
3. **Image Upload and Validation**
   1. The system shall validate file types like .jpg and .png and enforce file size limits when an admin uploads an image.
   2. Only admin shall upload or delete product details and images.
4. **Jewelry Search and Filtering**
   1. The system shall provide users the ability to search for specific categories such as rings, necklaces, etc.
   2. Users shall have the option to filter jewelry products by attributes such as material, design, or price range.
5. **Product Details and Display**
   1. A detailed view of each jewelry product, including a description, price, and images, shall be shown when a user selects an item from the gallery.
   2. Users shell explore the collection of jewelry by scrolling down
6. **Admin Management Capabilities**
   1. Administrators shall be able to manage user profiles, uploaded pictures, and product listings.
   2. Admin shall have the capability to upload images of jewelry to the store's collection, and the system shall supply a preview option before submission.


# Non-Functional Requirements

1. **Performance and Scalability**
   1. The system shall be scalable to handle an expanding number of clients, and concurrent associations without execution debasement.
   2. Each page and image gallery shall load within 2 seconds, even under high traffic conditions.
2. **Security and Data Protection**
   1. User personal information and passwords shall be encrypted before being saved in the database using hashing techniques.
   2.  All sensitive user information, including passwords, shall be encrypted using industry-standard encryption techniques.
   3.  The system shall enforce robust password policies, requiring users to create complex and secure passwords.
3. **Maintainability and Modularityn**
   1. The database shall be capable of scaling to accommodate increasing data loads, including new product images and details.
   2. The system shall ensure high availability by allowing users to access our platform even during high traffic times.
   3. The system shall be modular and maintainable, allowing developers to make necessary changes and fix bugs without affecting other components.
4. **Responsiveness and Compatibility**
   1. The system shall operate smoothly even with 100 users accessing the site concurrently.
   2. The system shall maintain compatibility with multiple browsers, including Chrome, Firefox, Safari, and Edge.
5. **Data Backup and Integrityy**
   1. The system shall conduct daily backups to avoid data loss, covering users, products, and inventory status.
   2. The system shall keep the user information in own database should not save in third party websites.
6. **User Experience and Accessibility**
   1. The system shall be fully responsive, guaranteeing ideal execution and ease of use over different gadgets like desktops, tablets, and smartphones.
   2. The system shall be smoot loading when user clicked on option or page.

