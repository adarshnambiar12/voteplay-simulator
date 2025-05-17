 # VotePlay Simulator 🗳️

VotePlay Simulator is a web-based educational platform designed to familiarize young teenagers with India's Electronic Voting Machine (EVM) and Voter Verifiable Paper Audit Trail (VVPAT) systems. The project addresses the crucial need for electoral literacy among future voters by providing an interactive and engaging simulation of the actual voting process. Built using modern web technologies including React.js, Node.js, and MongoDB, the platform ensures a secure, responsive, and user-friendly experience. The project serves as both an educational tool and a technical demonstration, effectively bridging the gap between electoral awareness and practical implementation of our Indian voting system.

### You can check it out at : [voteplay.tech](https://www.voteplay.tech)

## 🌟 Features

- **Authentication System**
  - Secure user registration and login
  - OTP verification for added security

- **EVM (Electronic Voting Machine) Simulation**
  - Realistic EVM interface replication
  - Interactive button controls
  - Authentic sound effects for button clicks

- **VVPAT (Voter Verifiable Paper Audit Trail) System**
   - Paper trail simulation after vote casting
   - Visual verification of the vote
   - Animated paper roll display
   - 7 seconds timer-based slip display system

- **Category-based Voting System**
   - Multiple voting categories (e.g. IPL teams, AI tools, browsers)
   - Category-specific candidate lists
   - Real-time vote counting
   - Result visualization

- **VoteCoin System**
   - Digital currency for platform interaction
   - Integrated payment gateway (Cashfree)
   - Cost structure:
     - 5 VoteCoins to cast a vote
     - 10 VoteCoins to view results

- **Dashboard Features**
   - Real-time voting statistics
   - User vote history
   - Sample Voter Id

- **Educational Components**
   - Interactive voting process guide
   - Information about Indian electoral system
   - Fun facts about voting and democracy
   - User-friendly interface for learning

- **Payment Integration**
  - Secure payment processing via Cashfree
  - Multiple subscription packages

- **Security Features**
   - Encrypted data transmission
   - Secure vote storage
   - Session management
   - Protected user informat
 
## 🛠️ Tech Stack

### Frontend
- React.js with Vite
- Zustand for state management
- Framer Motion for animations
- TailwindCSS for styling
- React Router for navigation

### Backend
- Node.js & Express
- MongoDB with Mongoose
- JWT authentication
- Nodemailer for OTP
- Cloudinary for image storage

## 🚀 Getting Started

### Prerequisites
- Node.js >= 14.x
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/adarshnambiar12/voteplay-simulator.git
```
2. Install backend dependencies
```bash
cd backend
npm install
```
3. Install frontend dependencies
```bash
cd frontend
npm install
```
4. Set up environment variables
```bash
#Backend (.env):
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email
EMAIL_PASSWORD=your_email_password
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
```
```bash
#Frontend (.env):
VITE_API_BASE_URL=http://localhost:5000/api
```
5. Start the development servers
```bash
#Backend
npm run dev
```
```bash
#Frontend
npm run dev
```

### Acknowledgments
- Election Commission of India

### Screenshots
![Screenshot 2025-05-17 122849](https://github.com/user-attachments/assets/eea8020b-a163-484f-8e65-7ea2de3e44cb)

![Screenshot 2025-05-17 122938](https://github.com/user-attachments/assets/0ff5f0d8-2895-46c2-a581-1deafac18fe6)

![Screenshot 2025-05-17 123009](https://github.com/user-attachments/assets/f1de4c26-3ec4-4b7d-bedb-95359fa14a2b)

![Screenshot 2025-05-17 123041](https://github.com/user-attachments/assets/f7dbb4b5-4b0b-4090-9e45-27b4aadf7ebc)
