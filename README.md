Library System Model

This project is an extended and tested USE (UML-based Specification Environment) model of a Library System. It was designed to simulate realistic scenarios such as borrowing, reserving, returning books, and handling fines.

The system builds on the initial model by introducing enums to track borrowing and reservation status, new operations for books, copies, and users, and refined constraints to enforce system rules. State machines capture the lifecycle of books and copies, while SOIL scripts provide automated testing of different scenarios, including edge cases.

Members of the system can borrow or reserve copies, with constraints ensuring that limits are respected and duplicates are avoided. Employees are able to apply fines up to a set threshold, while members can pay their fines to restore their borrowing privileges. The model also incorporates clear role separation by extending the Person class into Member and Employee, each with their own responsibilities. Book availability and reservation logic are managed through carefully defined constraints, making the system predictable and reliable.

Through this project I developed a deeper understanding of object-oriented modeling and the use of OCL constraints to enforce rules in complex systems. I gained practical experience in designing state machines to represent lifecycles, in extending class hierarchies to reflect different roles, and in using SOIL scripts to test functionality across a range of cases. 
