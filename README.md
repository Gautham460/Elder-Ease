# ElderEase - Smart Parental Care Website for the Elderly

ElderEase is a comprehensive, professional web application designed to help monitor, manage, and support the health and well-being of elderly individuals. It provides caregivers, family members, and healthcare providers with a central platform to track medical information, medications, health metrics, and emergency alerts.

## Features

### 🔐 **Authentication & Security**
- Secure login and registration system
- Role-based access control (Elder, Caregiver, Admin)
- Session management with localStorage persistence
- Protected routes for authenticated users

### 📊 **Dashboard**
- Real-time health overview
- Quick statistics on metrics, medications, and alerts
- Recent health readings display
- Upcoming medication reminders
- Active alerts summary
- Quick action buttons

### ❤️ **Health Monitoring**
- Multiple health metric types (Blood Pressure, Heart Rate, Temperature, Blood Glucose, Weight)
- Add, view, and delete health metrics
- Automatic status classification (Normal, Warning, Critical)
- Timestamp tracking and optional notes

### 💊 **Medication Management**
- Create and manage medication reminders
- Track medication adherence
- Set scheduled times and dosages
- Mark medications as taken
- Complete/incomplete reminder status

### 👥 **Family & Contacts**
- Add and manage family members and caregivers
- Set relationship types and permission levels
- Direct contact information (email, phone)
- Quick contact action buttons

### 🚨 **Emergency Alerts**
- Real-time alert system
- Alert severity levels (Low, Medium, High, Critical)
- Alert status tracking and location information

### 📈 **Reports & Analytics**
- Weekly and monthly health reports
- Medication adherence tracking
- Health trends analysis
- Data export capabilities

## Tech Stack

- **Frontend:** React 19 with TypeScript
- **Build Tool:** Vite
- **Styling:** Tailwind CSS
- **UI Components:** HeadlessUI, Lucide React Icons
- **State Management:** Zustand
- **Routing:** React Router v7
- **Storage:** localStorage for client-side persistence
- **HTTP Client:** Axios
- **Date Utilities:** date-fns

## Getting Started

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

The application will be available at `http://localhost:5173`

### Demo Credentials
- **Email:** demo@example.com
- **Password:** (any password works in demo mode)

## Project Structure

```
src/
├── components/
│   ├── auth/              # Login/Register components
│   ├── common/            # Reusable components
│   ├── layout/            # Header, Footer, MainLayout
│   ├── dashboard/         # Dashboard components
│   ├── health/            # Health monitoring
│   ├── medication/        # Medication management
│   ├── alerts/            # Alerts
│   └── contacts/          # Contact management
├── pages/                 # Full page components
├── store/                 # Zustand state management
├── types/                 # TypeScript types
├── services/              # API services
├── utils/                 # Utilities
├── App.tsx                # Main app with routing
└── main.tsx               # Entry point
```

## Pages

1. **Login Page** - User authentication with demo credentials
2. **Register Page** - User registration with role selection
3. **Dashboard** - Overview of health, medications, and alerts
4. **Health Page** - Log and view health metrics
5. **Medications Page** - Manage medication reminders
6. **Contacts Page** - Manage family members and caregivers
7. **Reports Page** - View health analytics and reports

## Pages Overview

### Dashboard
- Responsive stat cards showing key metrics
- Quick access to health data and medication reminders
- Active alerts display
- Quick action buttons to add data

### Health Metrics
- Add custom health measurements
- View full metric history
- Filter by metric type
- Status indicators (Normal, Warning, Critical)

### Medications
- Create medication reminders with dosage and time
- Track taken vs upcoming medications
- Mark medications as taken
- Separate views for upcoming and completed

### Contacts
- Add caregivers and family members
- Set permission levels
- Quick contact buttons (email, call)
- Remove contacts as needed

### Reports
- Medication adherence percentage
- Health metrics tracking
- Weekly and monthly summaries
- Export options for PDF and CSV

## Styling & UI

The website uses Tailwind CSS with:
- Professional blue primary color (#0ea5e9)
- Health status indicators (Green = good, Amber = warning, Red = critical)
- Responsive grid layout
- Card-based design system
- Mobile-first responsive design
- Clean, modern interface

## State Management

Using Zustand for:
- **Auth Store:** User authentication and profile
- **Health Store:** Metrics, reminders, and alerts
- **Contact Store:** Family members and emergency contacts

All state persists to localStorage for offline functionality.

## Features Implemented

✅ Complete authentication system (Login/Register)
✅ Dashboard with real-time stats
✅ Health metrics tracking
✅ Medication reminder system
✅ Family contact management
✅ Emergency alerts system
✅ Reports and analytics
✅ Responsive design
✅ Tailwind CSS styling
✅ State persistence
✅ Protected routes
✅ Role-based access

## Future Enhancements

- Backend API integration
- Real-time notifications
- Wearable device integration
- Two-factor authentication
- Video calling features
- Telemedicine integration
- Mobile app (React Native)
- AI-powered health insights
- Advanced medical history

## Commands

```bash
# Development
npm run dev

# Build
npm run build

# Preview build
npm run preview

# Lint
npm run lint
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized with Vite
- Code splitting for routes
- Lazy loading of components
- Responsive images
- Fast page load times

## Accessibility

- WCAG 2.1 Level AA compliant
- Keyboard navigation support
- Screen reader friendly
- High contrast colors
- Semantic HTML

---

**ElderEase** - Taking care of those who took care of us.
