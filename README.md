# VitualClassroomManager

The **VirtualClassroomManager** is a Java project designed to help instructors efficiently manage virtual classrooms. It provides features for creating classrooms, enrolling students, scheduling and submitting assignments, and managing classroom operations. This project uses essential software design patterns such as Singleton and Factory, ensuring scalability and ease of code maintenance.

## Features

- **Add Classroom:** Create new classrooms for managing students and assignments.
- **Enroll Student:** Add students to a classroom using their unique student IDs.
- **Schedule Assignment:** Schedule assignments for a specific classroom with assignment details.
- **Submit Assignment:** Allow students to submit assignments for a classroom.
- **View Classrooms:** Display a list of all available classrooms.
- **View Students in Classroom:** View all students enrolled in a specific classroom.
- **View Assignments in Classroom:** List all scheduled assignments for a classroom.
- **Delete Classroom:** Remove a classroom when it’s no longer required.

## Design Patterns

- **Singleton:** The `ClassroomManager` class follows the Singleton pattern, ensuring only one instance of the manager exists for organizing classrooms.
- **Factory:** The `AssignmentManager` simplifies the creation and management of assignment objects, streamlining the scheduling and submission process.

## Technologies Used

- **Java**
- **Java util library** for data structures (`HashSet`, `ArrayList`, `HashMap`)
- **Command-line interface (CLI)** for user interaction

## How to Run

- Clone the repository.
- Compile and run the `VirtualClassroomManager.java` file.
- Use the command-line menu to interact with the Virtual Classroom Manager and manage classrooms, students, and assignments.


