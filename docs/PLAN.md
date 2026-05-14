# Dwafjibk SaaS Plan

## Vision
Healthcare medication access platform connecting:
- users
- pharmacies
- distributors

## Roles
- ADMIN
- PHARMACY
- DISTRIBUTOR
- USER

## Backend Stack
- Laravel 11
- PostgreSQL
- Sanctum
- Docker

## Frontend Stack
- React
- Vite
- TailwindCSS
- Zustand
- React Query

## Main Modules
1. Authentication
2. Pharmacies
3. Medications
4. Reservations
5. Orders
6. Certificates
7. Notifications
8. Maps

## Database Entities
- users
- pharmacies
- medications
- reservations
- distributors
- orders
- payments
- medical_certificates

## Relationships

User:
- has many reservations

Pharmacy:
- has many medications
- has many reservations

Medication:
- belongs to pharmacy

Reservation:
- belongs to user
- belongs to pharmacy
- belongs to medication

## API Structure

/api/auth/*
/api/pharmacies/*
/api/medications/*
/api/reservations/*
/api/orders/*

## Development Order

1. Backend foundation
2. Auth
3. Pharmacies
4. Medications
5. Reservations
6. Frontend auth
7. Dashboards
8. Maps
9. Smart features