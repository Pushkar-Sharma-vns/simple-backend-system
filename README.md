# simple-backend-system
A backend system with User Registration and login with token-based authentication and CRUD operations on data.

1. Choice of Framework
For this project, I have chosen the Django framework. Django is a powerful and popular web development framework written in Python. Our decision to use Django was based on several key factors:

a. Full-Featured Web Framework:
Django provides a comprehensive set of tools and functionalities for building web applications rapidly. It comes with built-in features like an ORM (Object-Relational Mapper), templating engine, admin interface, authentication system, and more. This helps us focus on the application's core logic and saves development time.

b. Python Language:
Python is a versatile and easy-to-read programming language. It enables us to write clean, maintainable, and scalable code. Django being built on Python makes it a perfect match for our development team.

c. Active Community and Documentation:
Django has a large and active community of developers. This ensures that I have access to a vast range of third-party packages, extensions, and support. The abundance of documentation and tutorials also helps in overcoming challenges and learning best practices.

d. Versatile ORM:
Django's Object-Relational Mapper (ORM) abstracts the database layer, allowing us to work with the database using Python objects. This makes it easier to switch between different database engines without rewriting SQL queries.


2. Database Schema
The database schema for our project is designed to store information related to an online bookstore. The main entities in our schema are:

a. User:
    Fields: ID, username, email, password, date_joined, is_active, etc.
    Description: Stores information about the users of our application. It includes basic details like username, email, and password. The "is_active" field helps manage user         account status.

b. Dictionary:
    Fields: ID, key, value
    Description: Stores uniques key-value pair.
