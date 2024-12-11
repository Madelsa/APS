<div align="center">
  <img src="https://res.cloudinary.com/dhfysudgu/image/upload/v1732924918/wn5gljfdeujo2ajyaa11.svg" alt="SmartPark Logo" width="200"/>
  <br/>
  <br/>
  <h1 style="border: none;">
    🅿️ Abu Dhabi SmartPark System
    <br/>
    <small style="font-size: 16px;">AI-Powered Parking Solution</small>
  </h1>
  <p>
    <a href="#overview">Overview</a> •
    <a href="#features">Features</a> •
    <a href="#technical-architecture">Architecture</a> •
    <a href="#development-team">Team</a>
  </p>
  
  <br/>
  <img src="https://img.shields.io/badge/Status-MVP-blue" alt="Status"/>
  <img src="https://img.shields.io/badge/TypeScript-Next.js-blue" alt="Tech Stack"/>
  <img src="https://img.shields.io/badge/Database-MongoDB-green" alt="Database"/>
  <br/>
  <br/>
  <p>
    Discover the future of urban parking at <a href="https://parkit-ae.vercel.app" target="_blank">parkit-ae.vercel.app</a>
  </p>

  <p>
  For more details, check out our <a href="https://itsrain.ae/Parkit.ae-FAQ" target="_blank">FAQ</a> about the SmartPark System.
  </p>
</div>

---

## 🎯 Key Metrics

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%">
        <b>3,500</b><br/>
        Hours Saved/Day
      </td>
      <td align="center" width="25%">
        <b>60</b><br/>
        Seconds to Park
      </td>
      <td align="center" width="25%">
        <b>150%</b><br/>
        Revenue Increase for Abu Dhabi's Government
      </td>
      <td align="center" width="25%">
        <b>10K</b><br/>
        Daily Users
      </td>
    </tr>
  </table>
</div>

## 🌟 Overview

Abu Dhabi SmartPark is revolutionizing urban parking through AI-powered technology. Our system transforms the traditional parking experience by reducing search times from 15-20 minutes to under 60 seconds.

### 🎯 Problem Statement

- ⏰ Users waste 15-20 minutes daily searching for parking
- ⛽ Significant fuel waste from prolonged searches
- 🌍 Increased environmental impact from emissions
- 📊 3,500 collective hours wasted daily by 10,000 users

### 💡 Solution Benefits

- ⚡ Ultra-fast parking spot location
- 📈 150% revenue increase during peak hours
- 🚗 Improved urban mobility
- 🌱 Reduced environmental impact

## 🔥 Features

### 📍 Real-time Parking Availability
- Live occupancy tracking
- Interactive map interface
- Trend analysis
- ArcGIS integration

### 🎫 Smart Booking System
- Advance reservations
- Dynamic pricing model
  - Peak hours: 6:00 AM-9:00 AM & 6:00 PM-9:00 PM
  - Flexible rates for different parking types
- Secure payment integration

### 🤖 AI Assistant
- Natural language interface
- Smart recommendations
- Real-time updates
- Guided booking process

### 🔍 Search & Filters
```
├── Location search
├── Filter options
│   ├── Public parking
│   ├── Private parking
│   ├── Handicapped spots
│   └── Sheltered parking
└── Map customization
```

## 🛠 Technical Architecture

### Frontend
```
├── Next.js Framework
├── TypeScript
├── Tailwind CSS
├── ArcGIS Maps SDK
└── Custom UI Components
```

### Backend (MongoDB)
```
├── Collections
│   ├── ParkingSpots
│   ├── Bookings
│   ├── Users
│   ├── ParkingHistory
│   └── PricingRules
└── Features
├── Scalability
├── Real-time Updates
├── Complex Queries
├── Data Relationships
└── Geospatial Queries
```

## ⚡ Performance Metrics

<table align="center">
  <tr>
    <th align="center">Response Time</th>
    <th align="center">Update Frequency</th>
    <th align="center">Booking Speed</th>
    <th align="center">Map Loading</th>
  </tr>
  <tr>
    <td align="center">< 100ms</td>
    <td align="center">30 seconds</td>
    <td align="center">< 2 seconds</td>
    <td align="center">< 3 seconds</td>
  </tr>
</table>

## 🚀 Future Enhancements

<table>
  <tr>
    <td align="center">📱</td>
    <td><b>Mobile Applications</b><br/>iOS and Android native apps</td>
  </tr>
  <tr>
    <td align="center">🚗</td>
    <td><b>Vehicle Recognition</b><br/>Smart detection system</td>
  </tr>
  <tr>
    <td align="center">📈</td>
    <td><b>Predictive Analytics</b><br/>AI-powered availability forecasting</td>
  </tr>
  <tr>
    <td align="center">💳</td>
    <td><b>Enhanced Payments</b><br/>Multiple payment options</td>
  </tr>
  <tr>
    <td align="center">🏙</td>
    <td><b>Smart City Integration</b><br/>Connected infrastructure</td>
  </tr>
  <tr>
    <td align="center">🌍</td>
    <td><b>Emirates Expansion</b><br/>Coverage across UAE</td>
  </tr>
</table>

## 👥 Development Team

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/ItIsRain.png" width="100px" alt=""/>
      <br />
      <b>Mohamed Al Mehairbi</b>
      <br/>
      Team Leader, Developer & Student
      <br/>
      <i>Khalifa University</i>
    </td>
    <td align="center">
      <img src="https://github.com/Madelsa.png" width="100px" alt=""/>
      <br />
      <b>Mahmoud Abdelsalam</b>
      <br/>
      Graduated from Abu Dhabi University
      Developer & Student
      <br/>
      <i>42 Abu Dhabi</i>
    </td>
    <td align="center">
      <img src="https://github.com/alsaeed3.png" width="100px" alt=""/>
      <br />
      <b>Ali Saeed</b>
      <br/>
      Software Development
      <br/>
      <i>42 Abu Dhabi</i>
    </td>
    <td align="center">
      <img src="https://github.com/absalem42.png" width="100px" alt=""/>
      <br />
      <b>Abdullah Salem</b>
      <br/>
      Developer & Student
      <br/>
      <i>42 Abu Dhabi</i>
    </td>
  </tr>
</table>

## 📚 References

[1] Abu Dhabi Open Data Platform (accessed Nov. 18, 2024)

<details>
<summary>View Schema Definitions</summary>
  
Parking Spot Schema
```
interface ParkingSpot {
  _id: ObjectId;
  location: {
    type: "Point";
    coordinates: [number, number]; // [longitude, latitude]
  };
  type: "public" | "private" | "handicapped" | "sheltered";
  status: "available" | "occupied" | "reserved";
  pricePerHour: number;
  totalSpaces: number;
  availableSpaces: number;
  lastUpdated: Date;
}
```

Booking Schema

```
interface Booking {
  _id: ObjectId;
  userId: ObjectId;
  spotId: ObjectId;
  startTime: Date;
  endTime: Date;
  status: "active" | "completed" | "cancelled";
  price: number;
  paymentStatus: "pending" | "completed";
  createdAt: Date;
}
```
---

<div align="center">
  Made with ❤️ in Abu Dhabi
</div>
