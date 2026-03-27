FacilityConnect - Smart Facility Management

A comprehensive facility management platform with simulated real-time features, gamification, and multi-role support.

## ✨ Features

- **Service Requests** - Submit and track maintenance requests
- **Food Services** - Order food with Indian Rupee pricing
- **Room Booking** - Reserve meeting rooms and spaces (Users) / View bookings (Staff)
- **Live Chat** - Simulated real-time messaging between users and staff
- **Gamification** - Points, badges, and leaderboards
- **Analytics** - Performance metrics and insights
- **Multi-Role Support** - User and Staff dashboards

## 🚀 Quick Start

### 1. Install Dependencies
\`\`\`bash
npm install
\`\`\`

### 2. Run the Application
\`\`\`bash
npm run dev
\`\`\`

### 3. Open Your Browser
Navigate to `http://localhost:3000`

### 4. Login with Demo Accounts

**👤 User Account:**
- Email: `john@example.com`
- Password: `password123`

**👨‍💼 Staff Account:**
- Email: `sarah@example.com`
- Password: `password123`

## 🎯 How to Test Simulated Real-time Features

1. **Live Chat:**
   - Login as user in one browser tab
   - Login as staff in another tab
   - Click the chat button and send messages
   - See simulated message delivery and auto-responses

2. **Request Updates:**
   - Submit a maintenance request as user
   - Switch to staff account
   - Go to "Staff Panel" tab
   - Update request status
   - See instant notification simulation

3. **Online Status:**
   - See simulated online user count in chat
   - Watch simulated users join/leave messages

## 🛠️ Technology Stack

- **Frontend:** Next.js 14, React, TypeScript, Tailwind CSS
- **Backend:** Next.js API Routes
- **Real-time Simulation:** Mock Socket.IO implementation
- **UI Components:** shadcn/ui
- **Icons:** Lucide React

## 📱 Features Overview

### For Users:
- Submit service requests with priority levels
- Order food with Indian Rupee pricing
- Book meeting rooms
- Earn points and badges
- Simulated live chat with staff
- View personal analytics

### For Staff:
- Manage all service requests
- Update request statuses with simulated real-time updates
- View system analytics
- Order food (staff need to eat too!)
- View all room bookings (read-only)
- Communicate with users via simulated live chat
- Monitor facility operations

## 🎮 Gamification System

- **Points:** Earn points for every action
- **Levels:** Progress through levels
- **Badges:** Unlock achievements
- **Leaderboard:** Compete with other users
- **Streaks:** Maintain daily activity

## 🌟 Simulated Real-time Features

- **Live Chat:** Simulated instant messaging with auto-responses
- **Status Updates:** Simulated real-time request updates
- **Notifications:** Simulated instant alerts
- **Online Users:** Simulated active user count
- **Activity Feed:** Simulated live activity updates

## 🔧 Development

The application uses a mock Socket.IO implementation that simulates real-time features without requiring a WebSocket server. This makes it perfect for demo environments like v0.

### File Structure:
- `app/` - Next.js app directory
- `components/` - React components
- `lib/` - Utility functions, types, and mock socket implementation

## 🚀 Deployment

For production deployment:

1. Build the application:
\`\`\`bash
npm run build
\`\`\`

2. Start production server:
\`\`\`bash
npm start
\`\`\`

## 📞 Support

For any issues or questions, use the simulated live chat feature in the application or check the browser console for real-time simulation information.

---

**Built with ❤️ for modern facility management**
