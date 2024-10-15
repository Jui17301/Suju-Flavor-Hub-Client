SuJu Flavor Hub
Project Overview
SuJu Flavor Hub is a full-stack web application designed to bring together cooking enthusiasts, providing a platform for users to share, discover, and organize recipes. Targeting home cooks, culinary students, and anyone passionate about cooking, the platform allows users to post their favorite recipes, contribute interactive ingredient checklists, and share cooking time estimates. The community fosters the sharing of culinary knowledge and supports social engagement.

Key Features
User Registration: Create an account with email, password, and profile details.
Recipe Submission: Post detailed recipes with ingredient lists and images.
Interactive Features: Ingredient checklists and a built-in cooking timer.
Social Engagement: Commenting, rating, following users, and upvoting/downvoting posts.
Premium Membership: Access exclusive content through a subscription model.
Project Objectives
Frontend and Backend Development: Build separate components for a complete web application.
Authentication & Authorization: Secure user authentication with JWT for logged-in sessions.
Database Integration: Implement a MongoDB database for storing recipe data, user profiles, comments, and ratings.
Responsive UI/UX Design: Create a mobile-friendly interface with responsive design.
Advanced Search: Implement search functionality with filters for ingredients, cooking times, and categories.
Payment System: Integrate online payment solutions for membership subscriptions.
Functional Requirements
1. User Authentication & Authorization
User Registration: Account creation with email and profile details.
Login & JWT-based Authentication: Secure login with JWT tokens.
Password Recovery: Password reset functionality via email.
2. User Profile Management
Profile Customization: Update personal information and profile picture.
Social Connectivity: Follow/unfollow other users.
Premium Membership: Purchase subscriptions for premium content.
3. Recipe Management
My Recipes: Display submitted recipes with filtering and sorting options.
Recipe Sharing: Rich text editor support for formatting recipes.
Ingredient Checklist: Track gathered ingredients interactively.
Timer Functionality: Built-in timer for tracking cooking durations.
Recipe Deletion: Manage recipes easily with delete options.
4. Rating, Commenting & Upvote/Downvote System
Rate Recipes: Users can rate recipes (1 to 5 stars).
Commenting: Leave comments and edit/delete them.
Upvote/Downvote: Rank recipes based on user votes.
5. Recipe Feed
Dynamic Recipe Display: Show recipes with title, image, and rating.
Advanced Search & Filter: Search recipes by keywords and tags.
Infinite Scroll: Seamless browsing experience.
6. User Management
Admin Controls: Manage users and recipes, including account blocking.
User Interface Design
Required Pages
Login/Registration Page: Secure forms for user registration and login.
User Dashboard: Displays submitted recipes and profile options.
Admin Dashboard: Manage recipes and user accounts.
Recipe Feed: Lists all recipes with filtering and searching options.
Recipe Details Page: Detailed view of recipes with comments and ratings.
Profile Page: User profiles with their recipes and social connections.
About Us Page: Information about the platform.
Contact Us Page: A contact form for inquiries and support.
Design Guidelines
Color Scheme: Warm, inviting colors to reflect the culinary theme.
Navigation: User-friendly navigation for easy access to content.
Mobile-Friendly: Ensure responsiveness across all devices.
Bonus Requirements
Micro Animations: Smooth transitions and hover effects for a polished user experience.
Payment Integration: Subscription payments for premium content access.
Content Ranking: Upvote/downvote system to prioritize popular content.
Optional Requirements
Social Media Integration: Allow users to share recipes on social platforms.
Technologies Used
Frontend Development:
Next.js
Redux
TypeScript
Backend Development:
Node.js
Express
Mongoose
Database:
MongoDB
Installation
Clone the Repository:

git clone Client : https://github.com/Jui17301/Suju-Flavor-Hub-Client.git
git clone Server : https://github.com/Jui17301/Suju-Flavor-Hub-Server.git
Install Dependencies:
npm install
Backend Configuration:
Navigate to the backend folder:

cd SuJu-Flavor-Hub-Server
Create .env File:
Create a .env file in the backend directory and add the following environment variables:

PORT=5000
NODE_ENV=development
BYCRIPT_PASS=12
DEFAULT_PASS=suju8788
DATABASE_URL=mongodb+srv://sujuRecipe:suju8788@cluster0.fwhk0w8.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
JWT_ACCESS_SECRET=access_secret 
RESET_PASSWORD_EMAIL=sumaiyaalhasan2@gmail.com
RESET_PASSWORD_PASSWORD=87888788
STORE_ID=aamarpaytest
SIGNATURE_KEY=dbb74894e82415a2f7ff0ec3a97e4183
PAYMENT_URL=https://sandbox.aamarpay.com/jsonpost.php
PAYMENT_VERIFY_URL=https://sandbox.aamarpay.com/api/v1/trxcheck/request.php

Start the Backend Server:
npm start dev
Frontend Configuration:
Navigate to the frontend folder:

cd Suju-Flavor-Hub-Client
Install Frontend Dependencies:
npm install --legacy-peer-deps
Start the Frontend Development Server:
npm run dev

Admin
suju@gmail.com
Suju8788

License
This project is licensed under the MIT License. See the LICENSE file for more details.