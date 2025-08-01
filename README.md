# BandDevs

**Elite IT development team delivering cutting-edge digital solutions**

BandDevs is a modern, responsive web application showcasing our development team's capabilities, services, and portfolio. Built with React, TypeScript, and deployed on Cloudflare Workers with D1 database integration.

## 🚀 Features

- **Modern React Application**: Built with React 19, TypeScript, and Vite for optimal performance
- **Responsive Design**: Fully responsive design using Tailwind CSS with dark/light mode support
- **Interactive UI**: Smooth animations and transitions powered by Framer Motion
- **Contact System**: Integrated contact form with email notifications via Resend API
- **Database Integration**: Cloudflare D1 database for storing contact messages
- **Team Showcase**: Dynamic team member profiles with skills and social links
- **Project Portfolio**: Detailed project showcases with technologies and case studies
- **Service Offerings**: Comprehensive display of development services

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern React with latest features
- **TypeScript** - Type-safe development
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **React Router** - Client-side routing
- **Lucide React** - Beautiful icons

### Backend
- **Hono** - Fast web framework for Cloudflare Workers
- **Cloudflare Workers** - Serverless runtime
- **Cloudflare D1** - SQLite-compatible database
- **Resend** - Email API for contact form notifications
- **Zod** - Schema validation

### Development Tools
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Wrangler** - Cloudflare development CLI

## 📋 Services Offered

- **Web Development** - Modern, responsive web applications
- **Mobile App Development** - Cross-platform and native mobile apps
- **UI/UX Design** - Intuitive user interfaces and experiences
- **QA Testing** - Comprehensive testing strategies
- **AI Integration** - Smart AI-powered features and ML solutions
- **Tech Consulting** - Strategic technology guidance and architecture

## 👥 Team

Our diverse team includes:
- **Project Manager** - Coordinating cross-functional teams
- **Full-Stack Developers** - Frontend and backend specialists
- **UI/UX Designers** - Creating exceptional user experiences
- **QA Engineers** - Ensuring quality and reliability
- **DevOps Engineers** - Infrastructure and deployment specialists

## 🎯 Featured Projects

### Kape Pilipino
Modern Filipino coffee website with e-commerce functionality
- **Technologies**: HTML, Tailwind CSS, JavaScript, PHP, MySQL
- **Features**: Product management, order processing, responsive design

### MCP IT Helpdesk System
Automated helpdesk system with email notifications
- **Technologies**: HTML, Tailwind CSS, JavaScript, PHP, MySQL, Gmail SMTP
- **Features**: Hardware replacement requests, approval workflows

### CHOIMS (City Health Inventory Management System)
Inventory management for City Health Offices
- **Technologies**: HTML, CSS, JavaScript, PHP, MySQL
- **Features**: Role-based access, multi-location deployment

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- Cloudflare account (for deployment)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd BandDevs
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file with:
   ```env
   RESEND_API_KEY=your_resend_api_key
   ```

4. **Run development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

### Database Setup

1. **Create D1 database**
   ```bash
   npx wrangler d1 create your-database-name
   ```

2. **Run migrations**
   ```bash
   npx wrangler d1 migrations apply your-database-name
   ```

### Deployment

1. **Deploy to Cloudflare**
   ```bash
   npx wrangler deploy
   ```

2. **Set environment variables**
   ```bash
   npx wrangler secret put RESEND_API_KEY
   ```

## 📁 Project Structure

```
src/
├── react-app/           # Frontend React application
│   ├── components/      # Reusable UI components
│   ├── hooks/          # Custom React hooks
│   ├── pages/          # Page components
│   └── main.tsx        # Application entry point
├── worker/             # Cloudflare Worker backend
│   └── index.ts        # API routes and handlers
└── shared/             # Shared types and utilities
    └── types.ts        # TypeScript type definitions
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run check` - Type check and build validation
- `npm run cf-typegen` - Generate Cloudflare types

## 📞 Contact

- **Email**: hello@banddevs.com
- **Phone**: +63 966-561-5155
- **Location**: Manila, Philippines

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues and pull requests.

## 📄 License

This project is proprietary software owned by BandDevs.

---

*Building the future, one line of code at a time.*
