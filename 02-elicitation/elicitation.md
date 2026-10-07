# Week 2 - Elicitation

## Contents
1. [Stakeholder's Needs and Concerns](#stakeholder's-needs-and-concerns)
2. [Unknowns](#unknowns)
3. [Information Sources](#information-sources)
4. [Elicitation Questions](#elicitation-questions)
5. [Interview Notes](#interview-notes)
6. [Candidate Requirement](#candidate-requirement)

## 1. Stakeholder's Needs and Concerns
* **Students**
    * *Needs:* Clear visibility of available equipment, straightforward reservation process and explicit return deadline reminders.
    * *Concerns:* Equipment being double-booked or unavailable when needed for coursework and uncertainty over which staff member to cintact for collection or support.
* **Staff / Equipment Managers**
    * *Needs:* Efficient tracking of asseet locations, automated booking validations and reduced manual workload checking availability logs.
    * *Concerns:* Overdue equipment returns impacting other users, uncoordinated requests via email and informal channels and assets becoming damaged or lost.
*  **IT / System Administrators:**
    * *Needs:* Simple user role management and seamless integration with existing campus login credentials.
    * *Concerns:* High administrative overhead caused by technical issues or manual data entry errors in spreadsheets.
*  **Management / Department Heads:**
    * *Needs:* Complete oversight of high demand gear usage and equipment condition reports to justify future hardware budgets.
    * *Concerns:* Inefficient resource allocation and unreturned or damaged equipment.

## 2. Unknowns
* How long can a student or staff member keep borrowed equipment per loan period?
* What specific authorization levels are required to book high value or specialist gear versus standard items like laptops?
* How are overdue or late returns handled and are there automated notification/blocking rules enforced?
* What physical verification process is required when gear is physically picked up or handed back (e.g. manual check-in, barcode/QR code)?
  
## 3. Information Sources
* **Primary Sources:**
    * Interviews with equipment technicians and laboratory managers.
    * Feedback surveys from student and staff who regularly request shared gear.
* **Secondary Sources:**
    * Current booking logs, email records and spreadsheet templates.
    * Existing equipment inventory lists and college asset tracking policies.
 
## 4. Elicitation Questions

1. *To Students:* "What is your main challenge when trying to find out if specific equipment is available for an upcoming project?"
2. *To Staff:* "How do you currently verify that an item has been dafely returned before making it available to the next user?"
3. *To Equipment Manager:* "How do you handle situations where two people request the same piece of equipment at the same time?"
4. *To IT Support:* "What existing database or identity system should hold the authoritative equipment inventory list?"

## 5. Interview Notes
### Summary of Discussion with Equipment Manager
* Current email and spreadsheet bookings frequently result in double-booking conflicts and missing gear.
* Staff currently spend several hours per week manually checking availablility, answering contact inquiries and emailing late return reminders
* Confirmed that equipment must only be marked as "available" in the system ince it is Physically returned and inspected.

## 6. Candidate Requirement
1. (Functional): The system should allow authorized users to check real time item availability and submit booking requests for specified date and time slots.
2. (Functioanl): The system should prevent double-booking by immediately locking an item once reservation is confirmed for a specified date and time slots.
3. (Functional): The system should display the primary staff contact name and email on every equipment detail page.
4. (Non-Functional): Equipment booking confirmation messages should render on-screen within 5 seconds of submission.
