# Overview

This document outlines the functional and non-functional requirements for the jewelry store website aims to create an interactive web application, offering a seamless user experience for browsing and buying jewlery. Users can register or log in to view and buy jewelry products. Uploaded images will be stored in a database and displayed on the homepage in a smooth, interactive slider, providing an elegant way to explore the store's collection.

# Functional Requirements

**FR1:**
 System should give option for new users to register using their name, email ID and password.

**FR2:**
 The system should check for file type like .jpg, .png and file size when admin is uploading the image.

**FR3:**
 The system should show a chat option at bottom of the page to enquire about product to owner.

**FR4:**
 Users should be able to upload images of jewelry to the store's collection, with a preview option before submission.

**FR5:**
 The system should display uploaded images on the homepage in a smooth image slider for featured products.

**FR6:**
 A chat option should be available at the bottom of the page for users to directly inquire about products with the store owner.

**FR7:**
 Home page should have a search bar where users can search for product and category of jewellery with key words.

**FR8:**
 The system should send email notifications to users for successful registration, image uploads, and product inquiries.

**FR9:**
 The system should use JWT (JSON Web Token) for user authentication and authorization, ensuring secure login sessions.

**FR10:**
 Admins should have a dashboard to manage user inquiries, uploaded images, and product listings.

**FR11:**
 Users should be able to filter jewelry products by categories such as rings, necklaces, bracelets, etc.

**FR12:**
 The system should provide users with a responsive interface that works smoothly on mobile devices and tablets.

# Non-Functional Requirements

**NFR1:**
 System must work smoothly even if 100 concurrent users are accessing the site at the same time.

**NFR2:**
 User personal details and passwords must be encrypted before storing in database using hashing algorithms.

**NFR3:**
 Database should be able to scale up to handle increasing data loads of new product images and information.

**NFR4:**
 Backup should be taken daily to prevent data loss of users and products including inventory status.

**NFR5:**
 The web application should have a response time of less than 2 seconds for typical page loads, even under heavy load.

**NFR6:**
 The system should be compatible with major browsers (Chrome, Firefox, Safari, Edge) and various screen resolutions.

**NFR7:**
 The system should ensure a 99.9% uptime guarantee for users to access the site with minimal downtime.

**NFR8:**
 Error handling should be user-friendly, displaying appropriate messages for incorrect file uploads, login failures, and invalid search queries.

**NFR9:**
 Security best practices should be followed, including protection against SQL injection, CSRF, and XSS attacks.

**NFR10:**
 Image files should be optimized for fast loading times without compromising quality, ensuring smooth transitions in the image slider.

**NFR11:**
 The system should be designed with modular architecture, allowing future enhancements such as adding new features or updating existing ones without significant rework.

**NFR12:**
 The web application should be energy-efficient, minimizing resource consumption on both the client and server sides, ensuring sustainability and reduced operational costs.