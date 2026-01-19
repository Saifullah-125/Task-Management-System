# Task-Management-System

## Project Overview

A Java-based Task Scheduler application implementing core Data Structures and Algorithms with a user-friendly GUI. This project demonstrates practical applications of DSA concepts in a real-world task management system with persistent data storage.

## Data Structures Implemented

### **Priority Queue**

- **Purpose**: High-priority task scheduling

- **Implementation**: Ensures urgent tasks are processed first using heap-based prioritization

- **Use Case**: Task execution order management

### **Binary Search Tree (BST)**

- **Purpose**: Efficient task organization and retrieval

- **Implementation**: Tasks sorted by unique ID for O(log n) search operations

- **Use Case**: Quick task lookup and organized task hierarchy

### **Circular Queue**

- **Purpose**: Activity logging system

- **Implementation**: Maintains last 10 activities with efficient space utilization

- **Use Case**: Real-time activity tracking and history

### **HashMap**

- **Purpose**: Secure user authentication

- **Implementation**: Key-value storage for username-password pairs

- **Use Case**: Fast user lookup and secure login system

## Features

### Security & Authentication

- Secure login system with encrypted credentials

- Session management

- Protected access to task operations

### Task Management

- **Insert**: Add new tasks with priority levels

- **Delete**: Remove tasks by ID with automatic tree rebalancing

- **View**: Display tasks in organized formats

- **Search**: Efficient task retrieval using BST

- **Update**: Modify existing task details

### Real-time Operations

- Live task status tracking

- Priority-based scheduling visualization

- Instant activity logging

- Dynamic queue status display

### Data Persistence

- File-based data storage

- Automatic data backup

- Session persistence across application restarts

- Import/Export functionality

### User Experience

- Intuitive graphical user interface

- Responsive design with clear navigation

- Visual task hierarchy display

- Color-coded priority indicators

- Activity timeline visualization

## Technical Implementation

### **Core DSA Applications**

- **Priority Queue**: Task scheduling algorithm

- **BST Operations**: Insertion, deletion, traversal (in-order, pre-order, post-order)

- **Circular Queue**: Fixed-size buffer for activity logs

- **HashMap**: Collision handling and efficient retrieval

### **GUI Framework**

- Java Swing for interface components

- Event-driven programming model

- Real-time UI updates

- Thread-safe operations

### **File Handling**

- Serialization for object storage

- Text-based logging

- Configuration management

- Data validation on load

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher

- Any Java IDE (Eclipse, IntelliJ IDEA, NetBeans)

- Git for version control

### Installation

1. Clone the repository:

   ```bash

   git clone https://github.com/yourusername/task-scheduler-dsa.git

   ```

2. Open the project in your preferred Java IDE

3. Configure the project with JDK

4. Run `MainApplication.java`

### Compilation & Execution

```bash

# Compile all Java files

javac -d bin src/**/*.java

# Run the application

java -cp bin MainApplication

```

## Performance Analysis

### Time Complexities

- **Task Search**: O(log n) using BST

- **User Authentication**: O(1) average case with HashMap

- **Task Insertion**: O(log n) in BST

- **Priority Retrieval**: O(1) in Priority Queue

- **Activity Logging**: O(1) with Circular Queue

### Space Complexities

- **Overall**: O(n) where n is number of tasks/users

- **BST**: O(n)

- **HashMap**: O(n)

- **Circular Queue**: O(1) fixed size

## Testing

- Unit tests for each data structure

- Integration testing for complete workflows

- GUI functionality testing

- File I/O operations validation

## Future Enhancements

1. Multi-user collaboration

2. Cloud synchronization

3. Mobile application version

4. Advanced reporting and analytics

5. Email notifications

6. Task sharing capabilities

7. Advanced search filters

8. API development for third-party integration

## Team Contribution

This project was developed as part of the DSA course requirements with collaborative efforts in:

- Data structure implementation

- GUI design and development

- Algorithm optimization

- Testing and debugging

- Documentation

## Learning Outcomes

- Practical implementation of DSA concepts

- GUI development with Java Swing

- File handling and serialization

- Software design patterns

- Problem-solving and algorithm optimization

- Team collaboration and version control

