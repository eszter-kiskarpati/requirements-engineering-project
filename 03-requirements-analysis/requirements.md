# Week  - Requirements Analysis and Specification

## 1. Information from week 2
* **Key Stakeholders:** Students, Staff / Equipment Managers, IT / System Administrators, Management / Department Heads.
* **Core Problem:** Manual email and spreadgeet tracking leads to double-bookings, missing gear and heavy administrative issues.
* **Core Insight:** Equipment must only be marked as available once it is physically returned and inspected.

## 2. Candidate Requirements
* **FR-01:** The system shall allow an authorised user to view equipment availability for a selected date.

* **FR-02:** The system shall allow authorized users to check real-time item availablility and submit booking requests for specified date and time slots.

* **FR-03:** The system shall prevent double-booking by unnediately locking an item once a reservation is confirmed.

* **FR-04:** The system shall display the primary staff contact name and email on every equipment detail page.

## 3. Requirement Surgery
* **Vague Requirements** "The system shall be user-friendly."
    * **Problem:** "User-friendly" is subjective, immesurable and does not specify *who* it applies to or *how* ease of use is defined.
    * **Clarification Question:** "What specific task completion time or maximum training duration is expected for first-time student users?"
    * **Missing Information:** We do not know how fast it needs to be, what "easy to use" means to a student who is rushing or if any user testing was actually done.
    * **Repaired Requirement:** "First-time student user should be able to complete a standard equipment request in under 3 minutes without training."

## 4. Functional Requirements
* **FR-01 (View Availability):**
    * *Who:* Authorised users (students and staff)
    * *What:* The system shall allow an authorised user to view equipment availability for a selected date
    * *When:* When looking to reserve equipment for coursework or teaching
    * *Why:* To ensure equipment is available before promising or scheduling use
    * *How to Verify:* Test by logging in as a student, selecting a specific calendar date and verifying that the correct available/unavailable status matches the inventory

* **FR-02 (Prevent Double-Booking):**
    * *Who:* System / Equipment Manager
    * *What:* The system shall prevent double-booking by immediately locking an item once a reservation is confirmed
    * *When:* Upon successful booking confirmation
    * *Why:* To eliminate scheduling conflicts and overlapping reservations
    * *How to Verify:* Attempt to book an already reserved item for the same timeframe and confirm that the system blocks the transaction

## 5. Quality Requirements

## 6. Project Applications

## 7. Reflection

