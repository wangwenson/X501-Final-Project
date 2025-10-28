# Project Glossary

This glossary defines key terms and concepts used throughout the project.

---

## A

### API (Application Programming Interface)
**Definition:** A set of protocols and tools for building software applications.
**Usage:** The API endpoints are defined in the controllers directory.
**See also:** REST, Endpoint

---

## C

### CRUD
**Definition:** Create, Read, Update, Delete - the four basic operations of persistent storage.
**Usage:** The data_access layer implements CRUD operations for all entities.
**See also:** Data Access Layer, REST

### Controller
**Definition:** A component that handles HTTP requests and coordinates between models and views.
**Usage:** Controllers are implemented as Flask blueprints in the src/controllers directory.
**See also:** Blueprint, Route, MVC

---

## D

### Data Access Layer
**Definition:** An abstraction layer that encapsulates database operations.
**Usage:** All database queries should go through the data access layer.
**See also:** CRUD, Repository Pattern

---

## M

### Model
**Definition:** A representation of data structures and business logic.
**Usage:** Models are defined using ORM classes in the src/models directory.
**See also:** ORM, Schema

### MVC (Model-View-Controller)
**Definition:** A software design pattern that separates application logic into three interconnected components.
**Usage:** This project follows the MVC pattern with models, views, and controllers.
**See also:** Controller, Model, View

---

## O

### ORM (Object-Relational Mapping)
**Definition:** A technique for converting data between incompatible type systems using object-oriented programming.
**Usage:** SQLAlchemy is commonly used as an ORM in Flask applications.
**See also:** Model, Database

---

## R

### REST (Representational State Transfer)
**Definition:** An architectural style for designing networked applications using HTTP methods.
**Usage:** The API follows RESTful principles with standard HTTP methods.
**See also:** API, HTTP, CRUD

### Route
**Definition:** A URL pattern that maps to a specific controller action.
**Usage:** Routes are defined in controller files using Flask decorators.
**See also:** Controller, Endpoint

---

## V

### View
**Definition:** The presentation layer that renders data to users.
**Usage:** Views are HTML/Jinja2 templates stored in the src/views directory.
**See also:** Template, Jinja2

---

## Template for New Terms

### [Term Name]
**Definition:** [Clear, concise definition]
**Usage:** [Example usage in context]
**See also:** [Related terms]
