User Stories

1. User Registration

As a new user, I want to register an account with my email and password so that I can access the Airbnb Clone platform as a guest or host.





Acceptance Criteria:





I can enter my email, password, and role (guest or host).



The system validates my email is unique and my password meets security requirements.



Upon successful registration, I receive a confirmation email.



I can log in with my credentials after registration.

2. Property Booking

As a guest, I want to book a property for specific dates so that I can reserve a place to stay.





Acceptance Criteria:





I can select a property and specify check-in and check-out dates.



The system checks availability and prevents double bookings.



The system calculates the total cost based on the property’s price per night and booking duration.



I receive a booking confirmation with status set to “pending” or “confirmed.”

3. Make Payment

As a guest, I want to make a payment for my booking so that I can secure my reservation.





Acceptance Criteria:





I can choose a payment method (e.g., credit card, PayPal).



The system securely processes the payment via a gateway like Stripe.



I receive a payment confirmation notification.



The booking status updates to “confirmed” upon successful payment.

4. Add Property Listing

As a host, I want to add a new property listing so that I can offer it for guests to book.





Acceptance Criteria:





I can enter details like title, description, location, price per night, and amenities.



I can upload photos to the listing via a cloud storage service (e.g., AWS S3).



The system validates required fields and saves the listing.



The listing appears in search results for guests.

5. Leave Review

As a guest, I want to leave a review and rating for a property I booked so that I can share my experience with other users.





Acceptance Criteria:





I can submit a rating (1-5) and a comment after my stay.



The system ensures I can only review properties I booked.



The review is visible on the property’s listing page.



The host receives a notification about the new review.

6. Manage Bookings

As an admin, I want to manage bookings so that I can resolve disputes or monitor system activity.





Acceptance Criteria:





I can view a list of all bookings with details (e.g., guest, property, dates, status).



I can update booking statuses (e.g., cancel a booking).



I can filter bookings by status, date, or user.



Changes are logged for auditing purposes.

Project Context

These user stories are part of the Airbnb Clone project, designed to meet ALX project requirements. They are derived from the use case diagram in the use-case-diagram/ directory and complement the database schema (schema.sql) and sample data (seed.sql) in the alx-airbnb-database repository, as well as the backend requirements in the features-and-functionalities/ directory.

Created on June 27, 2025
