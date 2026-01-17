Tendering Platform – Backend

This repository contains the backend implementation of a Tendering Platform built using Node.js, Express, and MongoDB.
The system supports role-based access (Institute & Vendor), secure authentication, tender creation, bid submission, and document uploads.

#Features:

1.Authentication & Authorization

JWT-based authentication

Role-based access control (Institute / Vendor)

2.Institute Module

Create and manage tenders

View all bids submitted for a particular tender

Access uploaded bid documents

3.Vendor Module

View available tenders

Submit bids for tenders

Upload documents while bidding

4.File Uploads

Secure document uploads using Multer

5.Database

MongoDB with Mongoose ODM

6.RESTful APIs

Clean and structured API design

7.Security

Password hashing

Protected routes using middleware

#Tech Stack

Runtime: Node.js

Framework: Express.js

Database: MongoDB

ODM: Mongoose

Authentication: JWT (JSON Web Token)

File Uploads: Multer

Environment Config: dotenv

#User Roles

1.Institute

Create tenders

View bids on a specific tender

Download bid documents

2.Vendor

View published tenders

Submit bids

Upload bid-related documents

#Authentication Flow

User registers/logs in

Server generates a JWT token

Token is sent in headers for protected routes

Middleware verifies token & role access







