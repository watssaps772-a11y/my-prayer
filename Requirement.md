# My Prayer – Mini Prayer App Requirements Document

## 1. Application Overview

### 1.1 Application Name
My salati
### 1.2 Application Description
A lightweight mobile application designed to help Muslims pray on time and correctly, featuring a simple and user-friendly interface. The app provides essential prayer tools including prayer times, Qibla direction, prayer guides, and after-prayer supplications.

### 1.3 Application Type
Mobile Web Application

## 2. Core Features

### 2.1 Prayer Times\n- Display daily prayer times (Fajr, Dhuhr, Asr, Maghrib, Isha) based on user location
- Automatic location detection\n- Prayer time notifications to remind users
- Show remaining time until next prayer

### 2.2 Qibla Direction
- Display Qibla direction using compass functionality
- Visual compass interface showing direction to Mecca
- Option to manually enter city for Qibla calculation
- Location-based automatic Qibla detection

### 2.3 How to Pray
- Step-by-step guide for performing each prayer
- Number of rak'ahs for every prayer (الفجر: 2, الظهر: 4, العصر : 4, المغرب : 3, العشاء: 4)\n- Prayer texts and recitations:\n  - Rukūʿ (bowing) supplications
  - Sujūd (prostration) supplications
  - Tashahhud (sitting) recitations
- Clear instructions for each prayer position

### 2.4 After-Prayer Adhkar
- Written supplications (adhkar) to recite after each prayer
- Digital tasbih counter for dhikr tracking
- Common adhkar including:
  - Subhanallah (33 times)
  - Alhamdulillah (33 times)
  - Allahu Akbar (34 times)
- Reset counter functionality

## 3. Optional Features

### 3.1 Dark Mode
- Toggle between light and dark themes
- Automatic theme switching based on time of day

### 3.2 Adhan Sound
- Play adhan (call to prayer) at prayer times
- Multiple adhan sound options\n- Volume control\n
### 3.3 Prayer Tracking
- Mark prayers as prayed or missed
- Prayer history calendar view
- Statistics on prayer completion

### 3.4 Multi-language Support
- Support for multiple languages (English, Arabic, etc.)
- Language selection in settings

### 3.5 Prayer Learning Mode for Kids
- Simplified interface for children
- Interactive prayer learning guides
- Visual aids and animations

## 4. Technical Requirements

### 4.1 Technology Stack
- Frontend Framework: React + Tailwind CSS + Shadcn\n- Prayer Times API: Aladhan API or similar
- Data Storage: Local storage or Firebase
- Geolocation API for location detection
- Compass API for Qibla direction

### 4.2 API Integration
- Integration with prayer times API for accurate prayer schedules
- Location services for automatic city detection
- Compass sensor access for Qibla direction

## 5. User Interface Requirements

### 5.1 Design Principles
- Simple and clean interface
- Easy navigation between features
- Clear typography for readability
- Intuitive icons and buttons
\n### 5.2 Main Screens
- Home screen with current prayer time and countdown
- Prayer times screen with full daily schedule
- Qibla compass screen
- Prayer guide screen with step-by-step instructions
- Adhkar screen with tasbih counter
- Settings screen for preferences

## 6. Functional Requirements

### 6.1 Location Services
- Request user permission for location access
- Automatic detection of user's city and country
- Manual city selection option
- Store location preferences

### 6.2 Notifications
- Push notifications for prayer times\n- Customizable notification settings
- Option to enable/disable notifications for specific prayers
- Notification sound options

### 6.3 Data Management
- Store user preferences locally
- Cache prayer times data\n- Sync settings across devices (optional)
\n## 7. Non-Functional Requirements

### 7.1 Performance
- Fast loading times\n- Smooth animations and transitions
- Efficient battery usage
- Minimal data consumption

### 7.2 Usability
- Intuitive user interface
- Accessible to users of all ages
- Support for both portrait and landscape orientations
- Responsive design for different screen sizes

### 7.3 Reliability
- Accurate prayer times calculation
- Reliable Qibla direction\n- Consistent notification delivery
- Offline functionality for core features
