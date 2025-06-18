# greenpawsVeterinary-Clinic
A small but growing veterinary practice providing pet healthcare services, vaccinations, and surgeries. Operated by two vets and an assistant, with increasing difficulty managing records.
Why This Idea Perfectly Fits the project Brief
Requirement	How it's met
 One specific small business	GreenPaws Veterinary Clinic
 Justifiable need	Paper-based management → lost history, poor vaccine tracking, inefficient queueing
 CRUD-focused proof of concept	Clients, Pets, Visit Records (all full CRUD)
 JavaScript frontend with API (no page refresh)	Vanilla JS fetch() calls to Node.js/Express API
 File-based or SQLite backend	Use JSON or SQLite for data storage
 Testing	Unit tests for CRUD + 1 integration test
Entities:
Pet Owners (Clients): Name, phone, CNIC (optional)

Pets: Name, species, breed, DOB, linked to an owner

Visit Records: Date, pet ID, symptoms, treatment, next due visit (for vaccinations, etc.)

CRUD Operations:
Create, update, delete pet and owner profiles

Record vet visits with details

View/search pets by owner or name
