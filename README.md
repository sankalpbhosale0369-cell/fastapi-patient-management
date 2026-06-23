# Patient Management API

A RESTful Patient Management System built using FastAPI and Pydantic that allows users to create, view, update, sort, and delete patient records.

## Features

* Create new patient records
* View all patients
* View a specific patient by ID
* Update patient information using partial updates
* Delete patient records
* Sort patients by height, weight, or BMI
* Automatic BMI calculation
* Automatic health verdict generation (Underweight, Normal, Obese)
* Request validation using Pydantic
* Error handling using HTTPException
* JSON-based data storage
* Interactive Swagger API documentation

## Technologies Used

* Python
* FastAPI
* Pydantic v2
* JSON Database
* REST API
* Swagger UI

## API Endpoints

* GET `/` - Home
* GET `/about` - About API
* GET `/view` - View all patients
* GET `/patient/{patient_id}` - View patient by ID
* GET `/sort` - Sort patients
* POST `/create` - Create patient
* PUT `/edit/{patient_id}` - Update patient
* DELETE `/delete/{patient_id}` - Delete patient

## Key Concepts Demonstrated

* REST API Development
* CRUD Operations
* Pydantic Models
* Computed Fields
* Data Validation
* Query Parameters
* Path Parameters
* Error Handling
* JSON Serialization
* API Design Best Practices
