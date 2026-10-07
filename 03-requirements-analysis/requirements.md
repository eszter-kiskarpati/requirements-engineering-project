# Week 3  - Requirements Analysis and Specification

## Contents
1. [Information from week 2](#1-information-from-week-2)
2. [Candidate Requirements](#2-candidate-requirements)
3. [Requirement Surgery](#3-requirement-surgery)
4. [Functional Requirements](#4-functional-requirements)
5. [Quality Requirements](#5-quality-requirements)
6. [Project Applications](#6-project-applications)
7. [Reflection](#7-reflection)

*[Back to README](/README.md)*

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

* **NFR-01 (Performance):**
    * *Quality Type:* Performance / Responsiveness
    * *Why it matters:* Students and staff need fast feedback furing high demand booking preiods to prevent session timeouts.
    * *How it can be checked:* Measure th esystem response time during load testing to ensure booking confirmation mesages render on screen within 5 sexonds of submission.

## 6. Project Applications
* **Selected Project Requirement Candidate:** A mechannism to track item check-in and automated late return flags
    * *Source:* Equipment technician feedback regarding unreturned equipment
    * *Analysis:* Needs a clear definition of when a late penalty or alert triggers
    * *Question for Stakeholder:* How many hours past the scheduled return time does the system officially flag an item as overdue?
    * *Verification Method:* Simulate a missed return deadline and check if the alert log updates
    * *Unknown:* Whether automated email warnings are sent directl to the person who borrowed equipment or if it requires manual trigger

## 7. Reflection

1. **What makes a requirement diffucult to understand?**
        
    Ambigous adjectives ("user-friendly", "effivient", "quick", etc.) and assumptions about user workflows make requirements hard to verify
2. **What information do we still need for the project?**
        
    Precise workflow permissions and notification triggers for overdue items
3. **Who could provide that information?0**
        
    The equipment technician or the system administrator

