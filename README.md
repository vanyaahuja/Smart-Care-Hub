# Smart-Care-Hub
## Overview

This project is a mobile application that provides hospital equipment rental services alongside AI-powered prescription scanning for medicine delivery. Users can rent medical supplies like beds, monitors, and BiPAP machines, as well as order medicines by scanning their prescriptions. The app ensures secure transactions, pharmacist verification, and prescription-based medicine orders.

## Features

Hospital Equipment Rental – Browse, rent, and track medical supplies.

AI-Powered Prescription Scanning – Handwriting recognition for prescriptions.

Pharmacist Verification – Ensures accuracy for unclear prescriptions.

Order Management & Logistics – Tracks rentals, deliveries, and returns.

User Authentication & Security – KYC verification for rentals and medical orders.

Alternative Medicine Suggestions – Recommends cheaper alternatives with similar salts.

Allergic Reaction Alerts – Displays potential allergies based on medical history.

## Technologies Used

Frontend: React Native (for cross-platform mobile app)

Backend: Node.js with Express (scalable API management)

Database: PostgreSQL + Firebase (structured data & real-time updates)

AI/ML: TensorFlow/Keras (prescription handwriting recognition)

Cloud Services: AWS/GCP (hosting & storage)

Payment Gateway: Razorpay/Stripe (secure transactions)

## Installation & Setup

### Prerequisites

Node.js & npm installed

PostgreSQL database set up

Firebase account for real-time updates

### Steps

Clone the repository:

`git clone https://github.com/your-repo/hospital-rental-app.git
cd hospital-rental-app`

## Install dependencies:

`npm install`

Set up the database:

`npm run db:migrate`

Start the server:

`npm start`

## API Endpoints

POST /scan-prescription – Upload a prescription image for AI processing.

POST /verify-kyc – Submit user documents for verification.

POST /rent-equipment – Rent a medical device.

POST /return-equipment – Return a rented item.

POST /payment – Handle secure transactions.

## Contribution Guidelines

We welcome contributions! Please follow these steps:

Fork the repository.

Create a feature branch: `git checkout -b feature-name`

Commit changes:  `git commit -m "Added new feature"`

Push to branch: `git push origin feature-name`

Open a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any queries or collaboration, reach out to vanya.23bce10137@vitbhopal.ac.in or visit our GitHub Repository.
