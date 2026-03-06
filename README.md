# Event-Management-System
A software modeling project that simulates the management of events such as conferences, concerts, and cultural activities. Includes UML diagrams covering use cases, class structure, sequence flows, and state transitions across multiple actors including organizers, attendees, staff, and administrators.

Project Description: Event Management System

1. Aim of the System
The primary goal of the Event Management System is to centralize and automate the lifecycle of an event—from initial planning and resource allocation to attendee registration and post-event reporting.
The system aims to:
Reduce Manual Effort: Automate repetitive tasks like ticket generation and email confirmations.
Improve Data Accuracy: Maintain a single source of truth for attendee lists, schedules, and venue availability.
Enhance Communication: Provide a seamless interface for organizers to interact with participants and vendors.
2. User Levels (Actors)
Here are the typical tiers for an EMS:
Administrator: They manage system settings, oversee all users, handle security configurations, and have the power to override data.
Event Organizer: The power user. They create events, manage budgets, book venues, track registrations, and generate reports.
Attendee: The end-user. They browse available events, register/buy tickets, receive notifications, and provide feedback.
Service Provider: External vendors (caterers, decorators) who can log in to view their specific task assignments and schedules.

3. General Requirements
Functional Requirements
User Authentication: Secure login/signup for all user levels.
Event Creation & Management: Organizers must be able to create, edit, or cancel events (including date, time, location, and description).
Registration & Ticketing: A portal for attendees to sign up and receive a unique digital ticket (QR code).
Financial & Payment Processing: Integration with a secure payment gateway (e.g., Stripe, PayPal) to handle transactions, generate automated tax receipts, and process refunds according to system rules.
Scheduling: A module to manage the timeline of sessions or sub-events within a larger event.
Resource Management: Tracking venue capacity, equipment, and staff assignments.
Notification System: Automated emails or SMS for registration confirmation or event updates.



Non-Functional Requirements
Performance & Response Time: The system must load catalog pages in under 2 seconds and process payment transactions in under 5 seconds to prevent user abandonment.
High Scalability: The architecture must seamlessly handle sudden, massive spikes in concurrent users (e.g., the moment tickets for a highly anticipated event go on sale) without degradation in service.
Data Integrity & Security: All user passwords must be hashed, and payment/Personal Identifiable Information (PII) must be encrypted in transit and at rest, adhering to standards like GDPR.
System Availability: The platform must guarantee an uptime of 99.9%, utilizing automated backups and failover servers to prevent data loss during hardware failures.
Interoperability: The system should expose secure APIs to allow users to export event schedules directly to external calendars (Google Calendar, Outlook).


