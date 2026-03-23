PadhaiSathi (पढाइ साथी) 🎓
The First Dedicated Tutor Booking Platform for Nepal

PadhaiSathi is a robust, two-sided online marketplace designed to connect students and parents with qualified tutors and educational institutes across the Kathmandu Valley. Built as a final year project, it replaces unreliable word-of-mouth searches with a structured platform featuring verified profiles, secure payments, and a double-sided commission model.
+4

🚀 Key Features
👤 User Roles & Profiles

Custom User Model: Role-based access for Students, Tutors, and Institutes.


Tutors: Detailed profiles with subjects, grade levels (SEE to University), hourly rates, and teaching modes (Online/In-person).
+1


Institutes: Profile listings for coaching centers and a built-in Vacancy Board to hire new teachers.
+1

🔍 Discovery & Matching

Advanced Search: Filter tutors by subject, location (Kathmandu areas), price, and rating.


Subscription-Gated Visibility: Tutors must maintain an active monthly subscription to appear in search results.
+1


Matching System: A structured workflow where tutors unlock student contact info and students confirm matches via secure commissions.

💳 Integrated Payments (Khalti)

Automated Commission: Handles a 10% tutor "unlock" fee and a 5% student "match" fee.
+2


Subscription Management: Monthly recurring payments for tutors and institutes to remain active.
+1


Secure Flow: Includes server-side verification, webhooks for idempotency, and full transaction logging.
+1

⚡ Technical Excellence

Background Tasks: Celery and Redis handle weekly email digests and 3-day subscription expiry reminders.
+3


Real-time Notifications: Django Signals trigger in-app and email alerts for new bookings and confirmed matches.
+1


API Documentation: Fully documented with Swagger UI and ReDoc via drf-spectacular.
+2

🛠️ Tech Stack
Layer	Technology
Backend	
Django 5 & Django REST Framework (DRF) 
+3

Database	
PostgreSQL 
+3

Auth	
JWT (SimpleJWT) with Email Verification 

Task Queue	
Celery + Redis (Task scheduling with Celery Beat) 
+1

Payments	
Khalti Payment API 
+3

Frontend	
Django Templates + Bootstrap 5 
+1

Deployment	
Railway / Render 
+3
