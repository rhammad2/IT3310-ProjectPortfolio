
# Week 7 Product Backlog: RCHN Patient Intake and Scheduling System

**Consultant:** Raian Hammad  
**Role:** Associate Consultant, NovaTech Consulting  
**Project:** Riverside Community Health Network (RCHN)  
**Date:** October 20, 2026

## 1. User Story Fundamentals

As a clinic receptionist, I want to see available appointment times so that I can schedule patients faster and avoid scheduling mistakes.

The "so that" part explains why the feature is important and how it helps clinic staff. It also helps the team understand the purpose of the requirement.

## 2. Product Backlog

### User Story 1: Standardize Intake Fields

**As a:** Clinic intake coordinator

**I want:** To use the same required patient intake fields at all six clinics.

**So that:** Patient information is consistent and staff can avoid mistakes.

**Acceptance Criteria:**
1. Given a staff member opens an intake form, when they enter patient information, then the same required fields appear at all six clinics.
2. Given a required field is empty, when staff try to submit the form, then the system asks them to complete it.

**Story Points:** 5  
**MoSCoW Priority:** Must Have

### User Story 2: View Available Appointments

**As a:** Clinic receptionist

**I want:** To see available appointment times for doctors.

**So that:** I can help patients book appointments faster and avoid scheduling problems.

**Acceptance Criteria:**
1. Given a receptionist opens the scheduling system, when they select a doctor, then the system shows available appointment times.
2. Given an appointment is already booked, when the receptionist checks available times, then that time is not shown as available.

**Story Points:** 8  
**MoSCoW Priority:** Must Have

### User Story 3: Warn About Scheduling Conflicts

**As a:** Scheduling coordinator

**I want:** To receive a warning when two appointments are scheduled at the same time.

**So that:** I can avoid double bookings and keep appointments organized.

**Acceptance Criteria:**
1. Given a time slot is already booked, when staff try to book another appointment at the same time for the same doctor, then the system shows a warning.
2. Given there is a scheduling conflict, when staff try to save the appointment, then the system prevents the double booking.

**Story Points:** 5  
**MoSCoW Priority:** Must Have

### User Story 4: Appointment Reminders

**As a:** Patient

**I want:** To receive a reminder before my appointment.

**So that:** I can remember my appointment and arrive on time.

**Acceptance Criteria:**
1. Given a patient has an upcoming appointment and has agreed to receive reminders, when the appointment is one day away, then the system sends a reminder.
2. Given an appointment is canceled, when the reminder time arrives, then the system does not send a reminder.

**Story Points:** 5  
**MoSCoW Priority:** Should Have

### User Story 5: View Patient Wait Times

**As a:** Clinic manager

**I want:** To see how long patients wait for appointments at each clinic.

**So that:** I can find delays and help improve patient service.

**Acceptance Criteria:**
1. Given a clinic manager opens the report, when they select a clinic, then the system shows the average patient wait time.
2. Given the manager selects multiple clinics, when they view the report, then the system compares wait times between those clinics.

**Story Points:** 8  
**MoSCoW Priority:** Could Have

### User Story 6: Customize Dashboard Colors

**As a:** Clinic staff member

**I want:** To change the dashboard colors.

**So that:** I can personalize how the dashboard looks.

**Acceptance Criteria:**
1. Given a staff member opens dashboard settings, when they select an available color theme, then the dashboard uses that theme.
2. Given a staff member saves their theme choice, when they open the dashboard again, then the selected theme appears.

**Story Points:** 2  
**MoSCoW Priority:** Won't Have This Release

## 3. Prioritization Rationale

### Must Have Justification

I marked View Available Appointments as Must Have because scheduling is an important part of the RCHN project. Clinic staff need to see available times to book appointments correctly and avoid mistakes. This feature supports the main goal of improving scheduling across the six clinics. It is important for the project, but it does not mean it must be completed in the first Sprint.

### Won't Have Rationale

I decided to leave Customize Dashboard Colors for a later time because it is not necessary for patient intake or scheduling. The team should focus on important features first. This feature could be reconsidered later if clinic staff request it and the project scope is approved to include it.

## 4. Backlog Reflection

### User Evidence Connection — Week 3

In Week 3, the clinic intake coordinator persona showed the need for a simpler and more organized intake process. This supports my story about using the same required intake fields at all six clinics. It helps staff collect patient information consistently and avoid mistakes.

### Scope Connection — Week 5

In Week 5, the project scope included replacing the patient scheduling system. My story about viewing available appointments supports this goal. It gives developers a clear task: show available appointment times for each doctor and make sure booked times are not shown as available.
