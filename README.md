# Turf Booking Platform

A full-stack responsive Turf Booking Website with separate Admin & Customer panels.

## Tech Stack

- **Frontend**: React + Tailwind CSS
- **Backend**: Node.js + Express
- **Database**: MongoDB
- **Authentication**: JWT
- **Integrations**: WhatsApp API, Google Sheets API
- **Deployment**: Vercel (Frontend) + Render/Railway (Backend)

## Project Structure

```
turf-booking-platform/
├── customer-website/        # Customer React App
├── admin-dashboard/         # Admin React App
├── backend/                 # Node.js + Express API
└── README.md
```

## Features

### Customer Website
- Modern sports-themed UI
- Home Page with hero section
- About Page
- Book Now Form with auto-batch detection
- MongoDB booking storage
- WhatsApp notifications
- Google Sheets integration

### Admin Dashboard
- Secure JWT authentication
- Dashboard with analytics
- Booking management (approve/reject)
- Revenue analytics (weekly/monthly/yearly)
- Live booking updates
- Customer WhatsApp confirmations
- Export to CSV/PDF

### Backend API
- RESTful APIs
- MongoDB integration
- JWT authentication
- WhatsApp integration (Twilio)
- Google Sheets API
- Double booking prevention

## Installation

### Prerequisites
- Node.js v14+
- MongoDB
- npm or yarn

### Backend Setup

```bash
cd backend
npm install
cp .env.example .env
# Update .env with your credentials
npm start
```

### Customer Website Setup

```bash
cd customer-website
npm install
npm start
```

### Admin Dashboard Setup

```bash
cd admin-dashboard
npm install
npm start
```

## Environment Variables

See `.env.example` in each folder for required environment variables.

## API Documentation

See `backend/API.md` for detailed API endpoints.

## Deployment

- **Frontend**: Deploy to Vercel
- **Backend**: Deploy to Render or Railway
- **Database**: MongoDB Atlas

## Author

Turf Booking Platform Team
