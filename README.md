# Nihal-MongoDB
MongoDB assignment
//📌 Overview

This repository contains a collection of MongoDB problem statements designed to help students and beginners practice database operations. The problems simulate real-world applications such as inventory systems, booking systems, trackers, and management platforms.

Each problem focuses on performing CRUD operations (Create, Read, Update, Delete) along with filtering, sorting, projection, indexing, and aggregation.

🎯 Objectives
Understand MongoDB document structure
Practice CRUD operations
Learn filtering and querying techniques
Use projection to display selected fields
Perform updates and deletions
Apply aggregation and indexing concepts
🧩 Problem Categories

The repository includes 30 real-world scenarios, such as:

☕ Coffee Shop Menu System
📇 Contact Book System
✅ To-Do List Manager
💰 Expense Tracker
🎬 Movie Watchlist
🏨 Hostel Room Allotment
🚗 Parking Lot Management
🎁 Gift Card System
📦 Courier Tracker
🏋️ Fitness Logger
💳 Subscription Management
🧑‍💼 Employee Attendance
📊 Online Polling System
🚕 Cab Booking System
🏥 Hospital Bed Tracker
🛒 E-commerce Wishlist
✈️ Travel Planner
🏭 Warehouse Inventory
🎵 Playlist Manager
🏦 Loan Application System
🍔 Delivery Rider Tracker
🏨 Hotel Feedback System
🎟️ Ticket Booking System
📱 Social Media Analytics
⚙️ Manufacturing Defect Tracker
⚙️ Requirements
MongoDB installed locally or MongoDB Atlas account
MongoDB Shell (mongosh) or MongoDB Compass
🛠️ Operations Covered

Each problem includes tasks like:

1. Create Collection
db.createCollection("collection_name")
2. Insert Documents
db.collection.insertOne({...})
db.collection.insertMany([...])
3. Retrieve Data
db.collection.find({ condition })
4. Projection
db.collection.find({}, { field1: 1, field2: 1 })
5. Update Data
db.collection.updateMany({}, { $set: {...} })
6. Delete Data
db.collection.deleteOne({ condition })
7. Aggregation
db.collection.aggregate([...])
8. Indexing
db.collection.createIndex({ field: 1 })
📂 Structure
/mongodb-practice
│── problem1.js
│── problem2.js
│── ...
│── problem30.js
│── README.md
🚀 How to Use
Clone this repository
Open MongoDB shell or Compass
Run the queries provided for each problem
Modify and experiment with queries to learn better
💡 Learning Outcomes

By completing these problems, you will:
Gain hands-on MongoDB experience
Improve query writing skills
Understand real-world database scenarios
Be ready for academic exams and projects
📜 License

This project is for educational purposes only.

//MongoDB Assignment D1– Set 1
📌 Overview

This project contains a set of MongoDB practice problems focused on building basic to intermediate database applications. It covers real-world scenarios like student management, product inventory, order systems, blogging platforms, and banking systems.

The goal is to understand how MongoDB works using practical examples and queries.

🎯 Objectives
Learn MongoDB basics
Perform CRUD operations (Create, Read, Update, Delete)
Work with arrays and embedded documents
Understand relationships (Embedding vs Referencing)
Implement transactions and indexing
🧩 Problems Included
1. 🎓 Student Record Management System
Manage student details like name, age, department, marks, and city
Perform insert, view, projection, and delete operations
2. 🛒 Product Inventory and Filtering System
Store product details (name, category, price, quantity, rating)
Apply filters like category and price range
Sort and update product data
3. 📦 Order Management System with Arrays
Manage customer orders with item arrays
Use $push to update arrays
Perform updates and deletions based on conditions
4. 📝 Blog Platform with Relationships
Design collections for users, posts, and comments
Implement relationships using embedding or referencing
Retrieve posts with comments
5. 🏦 Banking System with Transactions
Manage account details and transaction history
Perform deposit, withdrawal, and fund transfer
Ensure atomic transactions
Use indexing for performance optimization
⚙️ Technologies Used
MongoDB
MongoDB Shell (mongosh) / MongoDB Compass
🛠️ Key Operations Covered
Create Collection
db.createCollection("collection_name")
Insert Data
db.collection.insertOne({})
db.collection.insertMany([])
Read Data
db.collection.find({})
Projection
db.collection.find({}, { field: 1 })
Update Data
db.collection.updateOne()
db.collection.updateMany()
Delete Data
db.collection.deleteOne()
db.collection.deleteMany()
🚀 How to Run
Install MongoDB or use MongoDB Atlas
Open MongoDB Shell (mongosh) or Compass
Execute queries for each problem
Modify queries to practice more
📚 Learning Outcomes
Hands-on experience with MongoDB
Better understanding of NoSQL databases
Ability to design real-world database systems
Improved query writing and optimization skills
📜 Conclusion

This assignment helps in building a strong foundation in MongoDB by solving real-life problems step by step.
