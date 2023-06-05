# nestjs_project

break down the assignment

#1.  Develop a simple web admin application using NestJS & Micro-Services:
You need to create a web application using NestJS, a progressive Node.js framework.
Implement microservices architecture by dividing the application into smaller, independent services that communicate with each other. You should have a minimum of two microservices, and you can decide what functionalities they will handle.

#2. Various Roles:
The application should support multiple roles: Super Admin, Admin, Power User(s), Users, and Support Desk.
Each role will have different permissions and access levels within the application.

#3. Admin User Creation and Email Notifications:
Admin users should have the ability to create Power Users and regular Users.
When an Admin creates a user account for a Power User or User, the respective user should receive an email with a one-time password (OTP) link.
The OTP link should expire once the user is prompted to change their password.

#4. Session-based Authentication:
Implement session-based authentication for user login and authorization. This means that users will have a session after successfully logging in, and subsequent requests will be authenticated using session tokens or cookies.

#5. Email Service Integration:
Use appropriate email service libraries or APIs to send emails for user notifications, including the one-time password links.

#6. Super Admin and Group Management:
There should be only one Super Admin in the system.
The Super Admin should have the ability to create groups and assign Admin users to those groups.

#7. Group Data Isolation:
Group Admins should only have access to data within their respective groups.
Implement data isolation based on group assignments, ensuring that one Group Admin cannot see the data of another group.

#8. Power User Access:
Power Users should have access to view data of all Users.
Design the application to allow Power Users to access and retrieve data for all Users.

#9. Transaction Creation and Management:
Only Users should be able to create transactions, not Power Users.
Users should be able to create, delete, and view their own transactions.
Implement appropriate API endpoints and logic to enforce these restrictions.

#10. Support Desk Access:
Support Desk staff should only have the ability to view all transactions.
They should not be able to create, update, or delete any transactions.

#11. Transaction Format:
Transactions can be represented as simple text or PDF files.
Design the application to support the creation and storage of transaction data in either format.
