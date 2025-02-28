# Lunatic Guild Management System

## Overview

The Lunatic Guild Management System is a comprehensive web application designed to streamline operations for the Lunatic World of Warcraft guild, running on the Thrall realm. This full-stack application provides a robust platform for guild management, member interactions, and administrative tasks.

## 🌟 Key Features

### Authentication & User Management
- Discord OAuth2 integration
- Battle.net account linking
- Role-based access control
- Staff and member authentication

### World of Warcraft Character Management
- Battle.net character synchronization
- Character profile tracking
- Main character selection
- Item level and spec tracking

### Guild Application System
- Streamlined application process
- Staff review and management
- Configurable application settings
- Automated Discord notifications

### Support Ticket Management
- Create and manage support tickets
- Discord integration
- Staff-only ticket review
- Attachment support

### Discord Bot Integration
- Automated guild management
- Rules acceptance workflow
- Member role synchronization
- Welcome and onboarding processes

## 🔧 Tech Stack

### Backend
- NestJS (TypeScript)
- MongoDB
- Discord.js
- Battle.net API Integration

### Frontend
- Angular
- NgRx State Management
- Tailwind CSS
- TypeScript

### Key Technologies
- OAuth2 Authentication
- WebSocket Communication
- RESTful API Design
- Server-Side Rendering

## 🚀 Getting Started

### Prerequisites
- Node.js (20.x)
- MongoDB
- Discord Developer Account
- Battle.net Developer Account

### Backend Setup
1. Clone the repository
2. Install dependencies
   ```bash
   cd lunatic.backend.nest
   npm install
   ```
3. Configure environment variables in `.env`
4. Start the development server
   ```bash
   npm run start:dev
   ```

### Frontend Setup
1. Navigate to frontend directory
   ```bash
   cd lunatic.frontend.angular
   npm install
   ```
2. Configure environment files
3. Start the development server
   ```bash
   npm start
   ```

## 🔐 Environment Configuration

The application uses `.env` files for configuration. Key configurations include:
- Discord Bot Token
- OAuth2 Client Credentials
- MongoDB Connection String
- API and Frontend URLs

## 📋 Development Workflow

### Code Quality
- ESLint for TypeScript linting
- Prettier for code formatting
- Strict TypeScript configuration

### Testing
- Jest for unit and integration testing
- E2E tests for critical paths

## 🌐 Deployment

### Supported Platforms
- Local Development
- Docker
- Cloud Platforms (AWS, DigitalOcean)

### Deployment Strategies
- Continuous Integration
- Automated Deployments
- Environment-specific configurations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

### Contribution Guidelines
- Follow existing code style
- Write comprehensive tests
- Update documentation
- Ensure CI/CD checks pass

## 📄 License

MIT License

## 🏆 About Lunatic Guild

Lunatic is a competitive World of Warcraft guild on the Thrall realm, focusing on high-level Mythic raiding with a balanced, drama-free environment. Raid times: Saturday 22:00 CET.

## 🔗 Contact

- Discord: https://dc.lunatic-raid.ing
- Website: https://lunatic-raid.ing
- Email: admin@lunatic-raid.ing

---

**Built with ❤️ by the Lunatic Guild Tech Team**
