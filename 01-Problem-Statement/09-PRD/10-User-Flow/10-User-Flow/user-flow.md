# 🚆 RailEase — User Flow

## Primary Booking Flow

Open RailEase
↓
Search Train
↓
View Available Trains
↓
Select Train
↓
Select Class
↓
Enter Passenger Details
↓
Review Booking
↓
Make Payment
↓
Check Booking Status
↓
Booking Confirmed
↓
View Ticket / PNR

---

## Error Recovery Flow

Payment / Booking Issue
↓
Clear Status Message
↓
What happened?
↓
What is happening?
↓
What should I do next?

Check Status | Try Again | Get Help

---

# Information Architecture

RailEase
│
├── Home
│   ├── Search Trains
│   └── Upcoming Journey
│
├── Search Results
│   ├── Train Details
│   ├── Availability
│   └── Fare
│
├── Booking
│   ├── Passenger Details
│   ├── Review
│   └── Payment
│
├── Booking Status
│   ├── Processing
│   ├── Confirmed
│   └── Failed
│
├── My Journeys
│   ├── Upcoming
│   ├── Completed
│   └── Tickets
│
└── Help
    ├── Booking Issues
    ├── Payment Issues
    └── Login / OTP Issues

---

## MVP User Flow

Search → Select → Passenger Details → Review → Payment → Booking Status → Confirmation

Error Recovery should be available whenever something goes wrong.

---

## Key UX Principle

Every critical state should answer three questions:

1. What happened?
2. What is happening?
3. What should I do next?

> **Never leave the passenger wondering what happened.**
Then we'll take those wireframes into **Figma** and eventually turn RailEase into a portfolio-ready clickable prototype. 
