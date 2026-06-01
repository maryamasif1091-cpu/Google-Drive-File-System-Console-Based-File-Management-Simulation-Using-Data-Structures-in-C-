# ☁️ Google Drive File System (C++ Console-Based Simulation)

## Overview
The **Google Drive File System** is a C++ console-based project that simulates the core functionality of a cloud storage platform similar to Google Drive. It demonstrates how large-scale file management systems use data structures and algorithms to efficiently handle storage, access control, file sharing, versioning, and synchronization.

## ✨ Features

###  User Management
- User registration and login
- Logout functionality
- Password recovery using security questions
- Role-based user accounts (Viewer, Editor, Admin)

###  File & Folder Management
- Create, read, update, and delete files (CRUD)
- Store file metadata (name, type, size, owner)
- Tree-based folder hierarchy for organizing files and subfolders
- Fast file lookup using a hash table

###  Version Control
- Maintain multiple versions of files using linked lists
- Roll back to previous file versions when needed

###  Recycle Bin
- Deleted files are stored in a stack (LIFO)
- Restore recently deleted files

###  Recent Files Tracking
- Queue-based system for tracking recently accessed files
- Maintains access history in FIFO order

###  File Sharing & Permissions
- Share files between users
- Graph-based user relationship management
- BFS/DFS traversal for exploring sharing connections
- Role-based access control with read, write, and execute permissions

###  File Compression
- Run-Length Encoding (RLE) implementation
- Reduces storage space by compressing repeated characters

###  Cloud Synchronization
- Queue-based background synchronization simulation
- Handles file upload, update, and deletion operations

## 🛠 Data Structures Used
| Data Structure | Purpose |
|---------------|----------|
| Tree | Folder hierarchy |
| Hash Table | Fast file lookup and metadata storage |
| Stack | Recycle bin management |
| Queue | Recent files and cloud synchronization |
| Graph | File sharing and permission management |
| Linked List | File version control |

##  Functional Modules
- User Authentication System
- File CRUD Operations
- Folder Management System
- Version Control System
- File Sharing System
- Permission Management System
- Recycle Bin System
- Recent File Tracking
- Cloud Synchronization System
- File Compression Module

##  Learning Outcomes
This project demonstrates:
- Practical application of data structures and algorithms
- Cloud storage and file system design concepts
- Role-based access control (RBAC)
- Efficient data organization and retrieval techniques
- Software architecture principles used in platforms such as Google Drive, Dropbox, and OneDrive

##  Conclusion
This project showcases how a modern cloud storage system can be designed using fundamental data structures. By combining efficient storage mechanisms, access control, file versioning, and synchronization techniques, it provides valuable insight into the architecture of real-world file management platforms.
