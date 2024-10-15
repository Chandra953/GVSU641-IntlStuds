# Overview

This document outlines the functional and non-functional requirements for the jewelry store website aims to create an interactive web application, offering a seamless user experience for browsing and buying jewlery. Users can register or log in to view and buy jewelry products. Uploaded images will be stored in a database and displayed on the homepage in a smooth, interactive slider, providing an elegant way to explore the store's collection.

# Functional Requirements

**FR1:**
The system shall offer new users the ability to register by providing name, email address, and password.

**FR2:**
The system shall validate file types like .jpg and .png and enforce file size limits when an admin uploads an image.

**FR3:** 
The system shall feature a chat option at the page's bottom, enabling users to make inquiries about products with the store owner.

**FR4:**
Users shall have the capability to upload images of jewelry to the store's collection, and the system shall supply a preview option before submission.

**FR5:** 
The system shall allow users to register a new account or log in to an existing one using JWT authentication.

**FR6:** 
The system shall ensure that only authenticated users can upload images of jewelry items or access the chat feature with the store owner.

**FR7:** 
The system shall provide users the ability to search for specific jewelry pieces or filter them based on categories such as rings, necklaces, etc.

**FR8:** 
The system shall allow users to chat directly with the store owner regarding specific jewelry pieces.

**FR9:** 
Users shall be able to send queries or chat directly with the store owner about specific jewelry items.

**FR10:** 
Users shall have the option to filter jewelry products by attributes such as material, design, or price range.

**FR11:** 
A detailed view of each jewelry product, including a description, price, and images, shall be shown when a user selects an item from the gallery.

**FR12:**
Administrators shall be able to manage user profiles, uploaded pictures, and product listings.

# Non-Functional Requirements

**NFR1:**
The system shall operate smoothly even with 100 users accessing the site concurrently.

**NFR2:**
User personal information and passwords shall be encrypted before being saved in the database using hashing techniques.

**NFR3:**
The database shall be capable of scaling to accommodate increasing data loads, including new product images and details.

**NFR4:**
The system shall conduct daily backups to avoid data loss, covering users, products, and inventory status.

**NFR5:**
The system shall be scalable to handle an expanding number of clients, and concurrent associations without execution debasement.

**NFR6:**
The system shall ensure high availability by allowing users to access our platform even during high traffic times.

**NFR7:**
The system shall be modular and maintainable, allowing developers to make necessary changes and fix bugs without affecting other components.

 **NFR8:**
The system shall be fully responsive, guaranteeing ideal execution and ease of use over different gadgets like desktops, tablets, and smartphones.

**NFR9:**
The system shall maintain compatibility with multiple browsers, including Chrome, Firefox, Safari, and Edge.

**NFR10:**
 Each page and image gallery shall load within 2 seconds, even under high traffic conditions.

**NFR11:**
 All sensitive user information, including passwords, shall be encrypted using industry-standard encryption techniques.

**NFR12:**
The system shall enforce robust password policies, requiring users to create complex and secure passwords.
