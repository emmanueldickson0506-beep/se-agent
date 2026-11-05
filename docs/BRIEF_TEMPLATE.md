# Project Brief: CampusConnect UNT <App name>

## What we want
CampusConnect UNT is a web application designed to help University of North Texas (UNT) students discover and register for events organized by Registered Student Organizations (RSOs). The application provides a centralized platform where student organization leaders can publish events, manage registrations, and track student attendance, improving campus engagement.

## Users
UNT Students: Use smartphones or computers to browse campus events and register for activities, typically weekly.
RSO Leaders: Use the application to create events, manage registrations, and record attendance.
The application will support accessible forms, readable text, and keyboard navigation.

## Must do   (numbered; each one testable)
1. Allow UNT students and RSO leaders to create accounts, log in, and log out.
2. Allow RSO leaders to create events with a title, description, date, time, campus location, and maximum capacity.
3. Display upcoming UNT campus events and allow students to search by event title or RSO name.
4. Allow students to register for events while preventing duplicate registrations and registrations beyond capacity.
5. Allow students to view and cancel their event registrations.
6. Allow RSO leaders to view registered participants and record event attendance
7. Display registration and attendance totals for each event.

## Should do   (if time allows)
- Filter events by category, date, or campus location.
- Display students' event participation history.
- Export event attendance records to CSV.
- Provide reminders for upcoming registered events.

## Constraints
- Platform / technology: Responsive web application using HTML, CSS, JavaScript, Python Flask, and SQLite
- Data: Store user accounts, RSO information, event details, registrations, and attendance in SQLite. Passwords must be securely hashed.
- Cost: Use free, open-source tools without paid APIs or hosting requirements.
- Accessibility / privacy / legal: Support keyboard navigation, readable text, and accessible forms. Protect student information, restrict access to attendance records, and use fictional UNT-themed demonstration data

## Out of scope (so nobody builds it by accident)
- Integration with official UNT student login systems.
- Integration with UNT Engage or official university event management systems.
- Official RSO event approvals and Talons Up point awards.
- Payment processing and ticket sales.
- AI-powered event recommendations.
- Native Android or iOS applications.

## Quality expectations
- Separate frontend, backend, and database operations into organized modules.
- Use GitHub for version control and team collaboration.
- Write automated tests for event registration, duplicate prevention, and capacity limits.
- Validate user inputs and display clear error messages.
- Provide setup and execution instructions in README.md.

## Acceptance criteria
1. A UNT student can create an account, log in, and view upcoming campus events.
2. An RSO leader can create an event that appears in the campus event listing.
3. A student can register once for an event; duplicate or over-capacity attempts display errors.
4. A student can cancel a registration, making the available spot accessible to another student.
5. An RSO leader can record attendance and view accurate registration and attendance totals.

## Open questions
1. How will RSO leader accounts be authorized?
2. Will the application run locally or be deployed online?
3. What is the project development timeline?
