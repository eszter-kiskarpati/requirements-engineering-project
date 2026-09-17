# Week 1 - Initial Discovery

## Contents
1. [Facts](#1-facts)
2. [Assumptions](#2-assumptions)
3. [Unknowns](#3-unknowns)
4. [Stakeholders](#4-stakeholders)
5. [Goals](#5-goals)
6. [Scope](#6-scope)
    - [Part of the problem](#part-of-the-problem)
    - [Out of scope](#out-of-scope)
7. [Candidate Requirements](#7-candidate-requirements)
    - [Functional Requirements](#functional-requirements)
    - [Non-functional Requirements](#non-functional-requirements)
8. [Requirement Surgery](#8-requirement-surgery)
9. [Reflection](#9-reflection)

## 1. Facts
* The college would like an equipment booking system for student and staff use
* Currently the bookings are managed using email/spreadsheets/informal arrangements
* Return deadlines are not met
* Students have an issue with contacting personnel in charge
* The equipment can be double-booked

## 2. Assumptions
* Staff overview report
* Staff and students might have different priority levels
* People using the system has phone access
* The credentials used to access the system will match all the other sytem's credentials

## 3. Unknowns
* The allocated budget 
* How long can the borrowed equipment be kept
* Who should have access and on what level
* Equipment stock
* Automated or manual system
* What happens when equipment is returned damaged or late
* Is there a penalty or blocking system
* Is there physical hardware integration required (QR scanners, etc.)

## 4. Stakeholders
* Students - availability, ease of use
* Staff - availability, ease of use, equipment stock
* IT/System Admin - easy ways to fix technical issues
* Management/Department Heads - easily able to access any and all data
  
## 5. Goals
* Help the college keep the bookings organized
* Keep track of where and with who the equipment is
* Authorize users to request items for a certain date

## 6. Scope
### part of the problem
* Tracking equipment assignments and expected return dates
* Preventing double-booking of shared assets
* Standardizing how students contact staff for equipment inquiries

### out of scope
* Purchasing or sourcing new hardware for the college
* Managinf room/lab bookings (system is strictly for physical equipment)
* Maintanance/repair services for broken equipment

## 7. Candidate Requirements
### Functional Requirements:
* The system has to allow an authorised user to request equipment for a
  specified date and time
* Equipment that has been booked has to be flagged by the system to become
  unbookable
* Unavailable equipment shall only be put back on the available list once it's
  actually brought back and is physically available
* The staff has to be able to modify the stock list

### Non-functional requirements:
* Booking confirmation messages displays within 30 secs
* First-time student users should be able to complete a standard equipment request in under 3 mins without training

## 8. Requirement Surgery
  ***"Students are not always sure who to contact about equipment."***

  - flaws:
      - Who is the right contact for each item? 
      - How does a student know who manages what?
      - Should the system route inquiries automatically?

  - rewritten requirement:
  
  **"The system should display the primary staff contact name and email directly on the detail page of every listed equipment item.**
    

## 9. Reflection

Completing initial discovery showed how important it is to turn vague user complaints into clear, measurable requirements. 
Defining precise boundaries early prevents scope creep and ensures the final system actually solves the core issues.
