# MVP-Appointment-Booking

## Introduction

This Project is a demonstration about a marketplace to handle differents systems like service catalog, profesional systems, resources system, schedule, and availability engine to create an Appointment booking to organize the actors client, stylist, admin, and the establishment in advanced development.

## Scope

Initially, our focus will be on the Hair Staylist Sector, helping businesses manage service bookings. This approach aims to facilitate engagement with new clients and minimize no-shows. Since the app is a demo, the business model should offer the software for free for the next four months, and then charge a fee per appointment. The rollout will start in CDMX, integrating establishments and stylists. The system should account for the fact that users are reluctant to download a standalone app for a single task, and instead prioritize systems integration for the beauty sector.

## Domain Requirements

### Stylist

  1. Presentation
  2. Multiple specialties
  3. Independent agenda
  4. They could work in different buildings
  5. They have differents levels of expertiees
  6. They could be active, inactive, and on vacations

### Client

  1. Registry in the app
  2. Pick a valid appointment
  3. Appointment history
  4. Preferences about favorite style, recurrent service, allergy, and stylist.
  5. Color formula record
  6. Check the status of the appointment

### Administrator/Receptionist

  1. The services offered
  2. Sign the stylist working with them
  3. Business hours
  4. Booking rules
  5. Time to clean the space is not the same with each service-dependent

## Tecnical Requirements

1. Save the worker's profile in the database.
2. Link the worker's schedule to the availability of services offered by the business.
3. Mark appointments as pending, awaiting deposit, waitlist, expired, or completed.
4. Process payments on the platform.
5. Display the services. When one is selected, show the available time slots for an appointment.
6. Update only the status of an appointment.
7. For appointments scheduled more than two days in advance, send a reminder one day before the appointment.
8. View the daily schedule.
9. Create an appointment directly for the admin's own business.
10. Configure the business schedule.
11. Save the business location.
12. Track client no-shows

## Architecture Knowledge Management (AKM)

## Sub-systems

### Service Catalog

#### Beauty Salon

1. Hair Stylist: Haircuts, coloring, styling, and hair treatments such as deep conditioning, hair Botox, keratin straightening, and perms to repair or change your hair's texture.
2. Beauty and Aesthetics Services: Manicures, pedicures, professional makeup, and eyebrow shaping.
3. Facial and Body Care: Facials, relaxing massages, hair removal (waxing or laser), and exfoliating treatments.
4. Specialized Barbering Services: Beard shaping, classic straight-razor shave with hot towel, and hydrating facial rituals for men.
5. Image Consulting: Personalized consultations to help you select the perfect haircuts, colors, and products tailored to your face shape and hair type.
