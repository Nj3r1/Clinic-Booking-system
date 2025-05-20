# Clinic-Booking-system
This database is designed for a Clinic Booking System, managing patient appointments, doctor schedules, and medical records. It includes four main tables:

Patients: Stores patient information (name, contact details, etc.).

Doctors: Contains doctor details and their specializations.

Appointments: Tracks scheduled visits with status (Scheduled/Completed/Canceled).

MedicalRecords: Stores diagnosis, prescriptions, and notes linked to appointments.

Key Features:
✔ Relational Structure (1-to-Many, 1-to-1 relationships)
✔ Constraints (PK, FK, NOT NULL, UNIQUE)
✔ Appointment Conflict Prevention (Doctors can’t have overlapping bookings)
