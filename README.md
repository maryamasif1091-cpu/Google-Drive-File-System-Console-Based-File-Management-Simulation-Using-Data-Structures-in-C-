# Google Drive File System (C++ Data Structures Project)

##  Overview
This project is a console-based simulation of a cloud file management system inspired by Google Drive. It demonstrates real-world applications of data structures including trees, graphs, stacks, queues, hash tables, and linked lists.

##  Features

###  User Management
- Signup / Login system
- Password recovery with security question
- Role-based access (Viewer, Editor, Admin)

###  File System
- Create, Read, Update, Delete (CRUD)
- File metadata management using Hash Table
- File search optimization

###  Version Control
- File version history using Linked List
- Rollback to previous versions

###  Recycle Bin
- Deleted files stored using Stack
- Restore last deleted file

###  Recent Files System
- Tracks recently accessed files using Queue

###  File Sharing
- Graph-based user-to-user file sharing
- BFS and DFS traversal for user network

###  Permissions System
- Role-based access control using Graph model
- Read / Write / Execute permissions

###  Compression
- Run-Length Encoding (RLE) for file size optimization

###  Cloud Sync
- Queue-based background synchronization system

---

## Data Structures Used

| Data Structure | Purpose |
|----------------|--------|
| Tree | Folder hierarchy |
| Hash Table | Fast file lookup |
| Stack | Recycle Bin |
| Queue | Recent files + Cloud sync |
| Graph | User relationships + permissions |
| Linked List | File versioning |

---

##  How to Run
1. Compile the program:
```bash
g++ main.cpp -o drive 
