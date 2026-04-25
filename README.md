# Google Drive File System (C++ Console-Based Simulation)

## Overview
The Google Drive File System is a C++ console-based project that simulates a cloud storage platform similar to Google Drive. It demonstrates how real-world systems manage large-scale data efficiently using data structures and algorithms. The project focuses on file handling, user authentication, permissions, version control, file sharing, compression, and cloud synchronization.

## Features

### User Management System
The system supports user registration, login, logout, and password recovery using security questions. Each user is assigned a role (Viewer, Editor, Admin), which controls access permissions throughout the system.

### File Management System
Users can create, read, update, and delete files. Each file stores metadata such as name, type, size, and owner. A hash table is used for fast file lookup and to prevent duplication.

### Folder Structure
A tree-based structure is used to represent folders and subfolders, allowing hierarchical organization similar to real cloud storage systems.

### Version Control System
Each file maintains multiple versions using a linked list. Every update creates a new version, allowing rollback to previous states.

### Recycle Bin System
Deleted files are stored in a stack (LIFO structure), enabling restoration of the most recently deleted file.

### Recent Files System
A queue tracks recently accessed files and maintains access history in a FIFO manner.

### File Sharing System
A graph structure represents user relationships. Files can be shared between users, and BFS/DFS traversal is used to explore connections.

### Permission System
Role-based access control is implemented using a graph model. Users have permissions such as read, write, and execute based on their roles.

### File Compression
Run-Length Encoding (RLE) is used to compress file content by reducing repeated characters.

### Cloud Synchronization
A queue-based system simulates background synchronization of file operations like upload and delete.

## Data Structures Used
- Tree : Folder hierarchy  
- Hash Table : Fast file lookup and metadata storage  
- Stack : Recycle bin  
- Queue : Recent files and cloud sync  
- Graph : User sharing and permissions  
- Linked List : File version control  



## Functional Modules
- User authentication system  
- File CRUD operations  
- Version control system  
- File sharing system  
- Recycle bin system  
- Recent file tracking  
- Cloud synchronization system  

## Learning Outcomes
This project demonstrates:
- Real-world application of data structures  
- File system and cloud storage design concepts  
- Role-based access control implementation  
- Efficient data storage and retrieval techniques  
- System design principles used in platforms like Google Drive, Dropbox, and OneDrive  

## Conclusion
This project shows how complex cloud storage systems can be built using fundamental data structures. It highlights how efficient design, proper data organization, and algorithms enable scalable and secure file management systems.
