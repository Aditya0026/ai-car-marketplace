# AI Car Marketplace

A modern car marketplace platform with AI-powered features, dual console system, and comprehensive car management.


## 🚀 Features

### User Console
- Advanced filtering system with URL persistence (sharable filters)
- Test drive booking system
- EMI calculator for financing options
- Real-time working hours display
- Car browsing with detailed specifications
- Authentication system

### Admin Console
- Complete car inventory management (add, delete, update)
- Mark cars as sold
- Test drive request management (complete, pending, done, etc.)
- Real-time working hours configuration
- Notification system for new test drive requests

## 🛠️ Technology Stack

- **Frontend**: Next.js
- **UI Components**: shadcn/ui
- **Authentication**: Clerk
- **Database**: PostgreSQL with Prisma ORM
- **Backend API**: Supabase
- **Rate Limiting**: Arjet

## 📋 Prerequisites

- Node.js (v18.0.0 or higher)
- pnpm or npm (recommended)
- Supabase account
- Clerk account


## 🔐 Authentication

The platform uses Clerk for authentication with two distinct user roles:
- **Regular Users**: Can browse cars, save filters, book test drives, etc.
- **Admin Users**: Have access to the admin console for managing inventory and bookings

## 💾 Database Schema

The primary data models include:
- `Car`: Car details, pricing, specifications, availability
- `TestDrive`: Test drive bookings with status tracking
- `WorkingHours`: Configurable business hours
- `User`: User profiles and preferences

## 🔄 Filter System

The filter system is URL-based, allowing users to:
- Filter by make, model, year, price range, etc.
- Share filtered results via URL
- Save favorite filters

## 🧮 EMI Calculator

The EMI calculator allows users to:
- Input loan amount, interest rate, and tenure
- Calculate monthly payments
- View payment schedules
- Customize down payments

## ⚙️ Admin Features

### Car Management
- Add new cars with detailed specifications
- Update existing car details
- Mark cars as sold/unavailable
- Upload and manage car images

### Test Drive Management
- View all test drive requests
- Update status (pending, confirmed, completed, canceled)
- Send notifications to users

### Working Hours
- Set working hours for each day of the week
- Set special holiday hours
- Changes reflect immediately on the user console

## 📱 Responsive Design

The application is fully responsive and optimized for:
- Desktop browsers
- Tablets
- Mobile devices

## 🔄 API Rate Limiting

Arjet is implemented for rate limiting to:
- Prevent abuse
- Ensure fair usage
- Protect sensitive endpoints

## 📝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a merge request



© 2025 AI Car Marketplace. All rights reserved.
