# social-network-api

## Description

This project is an API for a social network web application, allowing users to share their thoughts, react to friends' thoughts, and create a friend list. Built with Express.js for routing and MongoDB using Mongoose ODM, this API handles unstructured data efficiently, making it suitable for a social media platform.

## User Story

AS A social media startup  
I WANT an API for my social network that uses a NoSQL database  
SO THAT my website can handle large amounts of unstructured data

## Acceptance Criteria

- Server starts and connects to MongoDB database using Mongoose.
- API GET routes return formatted JSON for users and thoughts.
- API POST, PUT, and DELETE routes enable creating, updating, and deleting users and thoughts.
- API routes for adding and removing friends, and creating and deleting reactions to thoughts.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/social-network-api.git
   cd social-network-api
