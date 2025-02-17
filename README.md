expressBookReviews 📚

A simple book review API built using Node.js and Express.js.

Overview:
This project allows users to view book details, submit reviews, and retrieve book ratings. It is a part of the IBM Node.js and Express Developer course on Coursera.

🟢 Certificate: https://www.coursera.org/account/accomplishments/certificate/CDTXXX7336FK

📚 Course Link: https://www.coursera.org/learn/developing-backend-apps-with-nodejs-and-express

Installation & Setup
Prerequisites
Ensure you have the following installed:

Node.js (v16 or later)
npm (Node Package Manager)

Clone the Repository-

git clone https://github.com/yourusername/expressBookReviews.git
cd expressBookReviews


Install Dependencies
npm install
Run the Server

node index.js
or
npm start

API Endpoints: 
Get All Books
GET /books
Returns a list of all books.

Get Book by ISBN
GET /books/:isbn
Returns details of a book with the given ISBN.

Submit a Review
POST /books/:isbn/review
Submit a review for a book.

Technologies Used
Node.js
Express.js
REST API

License
This project is for educational purposes and part of the IBM Node.js and Express Developer course.

